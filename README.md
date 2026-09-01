# 👋 Olá, eu sou o Willian!

Graduando em **Segurança da Informação** na **Fatec Americana “Ministro Ralph Biasi”**. Minha atuação concentra-se na intersecção entre **segurança cibernética, governança de dados e Inteligência Artificial Generativa (GenAI)**, com ênfase no mapeamento de riscos emergentes e adequação a *frameworks* de conformidade.

---

### 🛠️ Pesquisa e Desenvolvimento Independente
Os repositórios hospedados neste perfil refletem iniciativas de pesquisa pessoal e experimentação tecnológica. Estes projetos são estritamente independentes e desvinculados das atividades, escopos ou propriedades intelectuais conduzidas em âmbito corporativo. Neste ambiente isolado, exploro a aplicação de *frameworks* de conformidade técnica e governança de LLMs, bem como a experimentação com IA Agêntica, priorizando as seguintes verticais:

- **BOM (CycloneDX):** Estruturação e rastreabilidade de inventário multidomínio para ampliar a visibilidade sobre a cadeia de suprimentos de IA (*AI Supply Chain*).
- **Conteinerização (Docker):** Empacotamento e orquestração de serviços e *workloads* por meio de Docker Compose, visando ambientes reprodutíveis e isolados. 
- **Criptografia Pós-Quântica (PQC):** Aplicação de *Module-Lattice-Based Digital Signature Algorithm* **ML-DSA (CRYSTALS-Dilithium)**, padronizado pelo **NIST** no **FIPS 204**, para assinatura de artefatos de auditoria, estabelecendo uma camada criptográfica para verificação de integridade e rastreabilidade na cadeia de custódia de modelos de IA.
- **IA Soberana (*On-premise*):** Experimentação com modelos fundacionais de pesos abertos (*open-weight models*) em ambientes locais e isolados, priorizando a execução de *workloads* de IA sem exposição de dados confidenciais a serviços externos.

---
## 🔬 Projetos em Destaque

**[BOMSenso](https://github.com/williansdb/bomsenso)** · *Framework* Experimental (PoC)

*Framework* experimental para **governança técnica, rastreabilidade e atestação de segurança em sistemas de IA**. Executado em uma arquitetura com **Docker Compose e dois contêineres**, `Ollama` e `Jupyter`, implementa um **comitê multiagente** para análise de artefatos gerados pelas ferramentas da **OWASP**, *CycloneDX Generator* (`cdxgen 13.0.1`) e `dep-scan 6.3.0`, abrangendo `AIBOM`, `CBOM`, `HBOM`, `OBOM`, `SaaSBOM` e `SBOM`, além da geração e análise de **Vulnerability Disclosure Reports (VDR)**.

A indexação semântica é realizada com **LazyGraphRAG** e a orquestração com o ecossistema **LangChain**. A cadeia de custódia dos inventários é complementada por **atestação criptográfica pós-quântica com ML-DSA (FIPS 204)**, utilizando `liboqs 0.16.0`.



**[Rastreabilidade Operacional em Modelos Fundacionais Open-Weights](https://github.com/williansdb/tcc_ai_governance_llms) · TCC / Pesquisa**

Pesquisa focada na integração estrutural de BOMs multicamadas (`SBOM`, `ML-BOM` e `HBOM`), `VEX` e telemetria de inferência. Propõe um modelo de custódia de metadados chancelado por criptografia pós-quântica (`ML-DSA-65` via `liboqs 0.15.0`) para viabilizar auditorias técnicas e rastreabilidade na cadeia de suprimentos de IA.

---
### 💻 Stack Técnica

- **Python:** Automação de processos de segurança e auditoria, processamento de *logs* estruturados e desenvolvimento de *scripts* para experimentação. Uso de *Jupyter Notebooks* na implementação e documentação de Provas de Conceito (PoC).
- **Linux (Debian/Ubuntu):** Administração de sistemas, automação operacional e aplicação de políticas de *hardening*.
- **Infraestrutura e Redes:** Segmentação de tráfego e implementação de *firewalls* com *nftables*; instrumentação de telemetria e monitoramento contínuo com *Jaeger, Prometheus, Zabbix e Grafana*.
- **Segurança de Software & *Supply Chain***: Geração e análise de SBOMs com OWASP *CycloneDX* (*cdxgen*) e OWASP *dep-scan*; identificação, classificação e rastreabilidade de vulnerabilidades por meio de CVE (Common Vulnerabilities and Exposures) e CWE (Common Weakness Enumeration).
- **Segurança de IA:** Análise de superfície de ataque e modelagem de ameaças com referência aos *frameworks* MITRE ATLAS™, OWASP Top 10 *for* LLMs e OWASP Top 10 *for Agentic Applications*.

--->

### 📫 Contato
- **Pessoal:** wst.brito@gmail.com
- **LinkedIn:** [linkedin.com/in/willian-brito](https://www.linkedin.com/in/willian-brito/)
- **Lattes:** [Currículo Lattes](http://lattes.cnpq.br/3765107203567178)
- **ORCID iD:** [orcid.org/0009-0005-2035-1056](https://orcid.org/0009-0005-2035-1056)
