# AWS_CloudFormation_Infra-CodeGirls2025
Insights sobre a implementação de uma infraestrutura automatizada na AWS utilizando CloudFormation, aplicando os conceitos de Infraestrutura como Código (IaC).

Este repositório foi desenvolvido como parte do **Bootcamp AWS & Cloud Computing - Santander Code Girls 2025**, com o objetivo de implementar uma infraestrutura automatizada utilizando o AWS CloudFormation.  
A proposta deste desafio foi explorar o conceito de Infraestrutura como Código (IaC), aplicando na prática a criação, configuração e gerenciamento de recursos AWS a partir de templates YAML e JSON.

## O que é o AWS CloudFormation?

O AWS CloudFormation é um serviço da AWS que permite criar e gerenciar recursos de infraestrutura automaticamente, a partir de arquivos de definição chamados templates, escritos em YAML ou JSON.  
Esses templates descrevem tudo o que deve ser criado na nuvem — como EC2 Instances, S3 Buckets, VPCs, Subnets, Security Groups e muito mais — seguindo o princípio de Infraestrutura como Código (IaC).

# Criando minha Stack: 

- No Console AWS, acessei CloudFormation → Create Stack → With new resources (standard)
- Fiz upload do template em YAML. Defini um nome para a Stack, cliquei em Create Stack e aguardei até o status CREATE_COMPLETE.
- Verifiquei os recursos criados no console da AWS.

# Dicas Práticas para Trabalhar com CloudFormation
- Automatize tudo: use CloudFormation para padronizar ambientes (dev, test, prod) sem erros manuais.
- Divida templates grandes usando nested stacks para facilitar manutenção.
- Documente os recursos com Description para facilitar a leitura.

# Minha experiência
Criar uma infraestrutura automatizada com CloudFormation foi uma experiência extremamente enriquecedora. 
No início, configurar tudo via código parecia desafiador, mas à medida que o template ganhava forma, percebi como o processo se torna organizado, reproduzível e seguro. Foi interessante observar como um simples arquivo YAML pode representar uma estrutura completa na nuvem, e como o CloudFormation coordena a criação, configuração e interdependência dos recursos automaticamente.
