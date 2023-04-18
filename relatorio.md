# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 18/04/2023
Empresa: Abstergo Industries 
Responsável: Valdir Torres Borges

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa [nome da empresa], realizado por [nome do responsável pelo projeto]. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: 
- Implantar uso de access token opor meio do serviço Cognito. O uso do token é uma medida eficiente para acessos controlados e retrições de acessos a API's e por tempo determinado. Caso a aplicaçãp necessite de mais tempo posteriormente, por exemplo, basta fazer nova requisição

Medida 2: 
- Implantar Multi-factor authentication. Usar o MFA para aumentar a segurança do seu ambiente da AWS. Entrar com MFA requer um código de autenticação de um dispositivo MFA. Cada usuário pode ter no máximo 8 dispositivos MFA atribuídos

Medida 3: 
- Fornecer somente acesso programático aos desenvolvedores, ou seja, não formecer acesso console. Tal medida, evita que desenvolvedores fiquem acessando serviços que não tem a ver com seu papel e possíveis vulnerabilidades inerentes de um acesso console


## Conclusão
A implementação de ferramentas na empresa Abstergo tem como esperado obter mais segurança e um acesso mais direcionado as api's das aplicações prevenindo acessps indevidos ou inadequados por meio de access tokens por meio do serviço Cognito da AWS. Adiciona-se que a implantação de MFA mult-factor refroça e avita possíveis vulnerabilidades por roubo de senhas e o fornecimento de acesso programático sem console evita acssos não autorizados e indevidos evitendo gasto desnecessários por uso indevido de serviços que não necessários ao projeto, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos
https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_finding-unused.html acessado em 18/04/2023
https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_mfa_enable_virtual.html?icmpid=docs_iam_console#enable-virt-mfa-for-own-iam-user acessado em 18/04/2023
https://docs.aws.amazon.com/IAM/latest/UserGuide/id_roles_common-scenarios_federated-users.html acessado em 18/04/2022
https://aws.amazon.com/pt/cognito/ acessado em 18/04/2022
https://docs.aws.amazon.com/pt_br/IAM/latest/UserGuide/id_credentials_access-keys.html  acessado em 18/04/2022


Assinatura do Responsável pelo Projeto:

Valdir Torres Borges