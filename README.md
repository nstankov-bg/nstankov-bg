## 👋 About Me

Hi there! I'm Nikolay, a Senior DevOps Engineer with a strong background in Full-Stack Development. Serverless(💗Vercel, make me unemployed quickly!), AWS, and VSphere are not just buzz-words for me. I have a passion for developing efficient and scalable cloud(& hybrid) infrastructures, and I'm always eager to explore and learn new technologies. My coding experience spans across multiple languages and frameworks, including PHP, TypeScript, Go, Python.

In addition to my DevOps expertise, I have a keen interest in AI & ML, particularly in deep learning, LLM, LangChain, and creating custom models for document ingestion. As a blockchain enthusiast, I have experience with cryptocurrency and was part of [Alonzo Blue](https://cointelegraph.com/news/cardano-grows-closer-to-launching-smart-contracts-with-new-testnet), the first cohort of Plutus pioneers in the Cardano blockchain.

## Public Stats

[![My GitHub Stats](https://github-readme-stats.vercel.app/api/?username=nstankov-bg&count_private=true&theme=tokyonight&showicons=true)]()


## 💼 Technical Skills

- **Cloud Platforms**: AWS, Azure, Serverless
- **On-Prem Infrastructure**: From pulling cables through racks, to managing multiple datacenters via VSphere
- **Programming Languages**: PHP, TypeScript, Go, Python, Haskell
- **Frameworks**: Next.js, Express.js, Symfony, FastAPI, Gin, React (albeit front-end is my largest enemy)
- **Infrastructure as Code (IaC)**: Terraform, AWS CloudFormation(not preffered, but managed), Ansible, AWS Systems Manager
- **CI/CD**: Jenkins, GitLab CI/CD, GitHub Actions
- **Load Balancing**: Traefik, Nginx, AWS(suite of LBs)
- **Containerization & Orchestration**: dockerd ,containerd, Docker Swarm, Kubernetes(various flavors from K3S to EKS)
- **Custom Registry creation & Management**: Docker Registry v2, Harbor
- **Storage Systems**: NetAPP, Various CSI, Ceph, GlusterFS
- **Monitoring & Logging**: OpenTelemetry, Prometheus, Grafana, Loki, ELK Stack, AWS CloudWatch
- **Version Control**: Git, never SCM
- **AI & ML**: Deep Learning, LLM, LangChain, Custom Document Ingestion Models
- **Blockchain**: Cardano, Plutus
- **Platform Engineering**: Custom & Simple Ephemeral Environments, Maintenance of large codebases, hundreds of repositories, and building scalable metrics-aware infrastructure
- **Developer Experience**: Designing and implementing large-scale developer workflows, optimizing build pipelines, and fostering a culture of collaboration and knowledge sharing
- **Open-Source Contributions**: Active contributor to various open-source projects
- **Security**: Secrets management, code scanning, code quality, implementation of quality asurance automation tools(like Perfecto)

## 🎓 Certifications

- **Terraform Associate**: [View Certification](https://www.credly.com/badges/e95771b6-ea19-467f-bc2b-c2dd917f166e/public_url)
- **AWS Practitioner**: [View Certification](https://www.credly.com/badges/78cbe465-a264-410d-9d17-3e65eb539b70/public_url)
- **AWS Solution Architect Associate**: [View Certification](https://www.credly.com/badges/a08db99a-ece5-4655-82b8-156c30157249/public_url)
- **New Relic Full Stack Observability Practitioner**: [Pending Certificate(1-2 days), but passed exam](https://example.com)
- **WAS01 - Barracuda WAF-as-a-Service [View Certification](https://campus.barracuda.com/certification/verify/69eb20da2fd0a46216aabf633a34d105)
## 🛡️ Security & Code Quality

With years of experience in infrastructure as code, I have gained expertise in both Day 0 and Day 1 operations. I take security very seriously and want to believe I am proficient in secrets management, code scanning, and code quality. I have implemented numerous quality & security-focused automations, ranging from SonarQube through Snyk and into modern decentralized suites like Pyrsia.

In addition to implementing security best practices, I believe that maintaining high code quality is essential for building scalable and reliable systems. I'm experienced in using static code analysis tools, linters, and automated testing frameworks to ensure code is clean, efficient, and adheres to industry standards.

## 📚 Continuous Learning

I'm always looking to expand my knowledge and stay up-to-date with industry trends. Some topics I'm currently exploring include:

- Advanced Kubernetes concepts and tools, such as service meshes and policy management
- Distributed systems and microservices architectures
- Ethics and best practices in AI/ML development
- Applying DevOps principles to data engineering and data science workflows

## 🌟 Open-Source Contributions

As a dedicated advocate of open-source software, I actively participate in a variety of projects that resonate with my areas of expertise. My primary interests lie in projects focusing on cloud infrastructure, DevOps, AI & ML, and blockchain technologies. Through my contributions to open-source initiatives, I strive to share my knowledge, foster innovation, and help shape the future of the tech industry. In doing so, I am able to collaborate with like-minded professionals, enhance my skillset, and remain at the forefront of cutting-edge developments in the field.

## 📇 You made it this far, contact me!

To contact me, run the following Python script to reveal my email address:

### Prep
```bash
#!/bin/bash
pip3 install requests==2.28.2 pgpy==0.6.0
```
### Run
```python
#grandReveal.py

import requests
import pgpy

url = "http://keyserver.ubuntu.com/pks/lookup?op=get&search=0x4540ff917ddc6743ddcb836c1741ef172011acf9"
response = requests.get(url)

if response.status_code == 200:
    gpg_key = response.text
    key, _ = pgpy.PGPKey.from_blob(gpg_key)
    user_id = key.userids[0]
    name = user_id.name
    email = user_id.email
    print("Name:", name)
    print("Email:", email)
else:
    print("Failed to fetch the GPG key.")
```
