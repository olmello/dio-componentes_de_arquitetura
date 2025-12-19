# Passo 1: Configuração do Ambiente
- Criação de conta Azure gratuita (se necessário)
- Acesso ao portal Azure (portal.azure.com)
- Configuração inicial do diretório ativo

# Passo 2: Implementação Prática
Criação de Grupos de Gerenciamento

## Exemplo de estrutura criada:
- Grupo de Gerenciamento Raiz
  ├── Produção
  ├── Desenvolvimento
  └── Sandbox

No meu caso, como em ambiente somente voltado para estudos, criei somente o de desenvolvimento.

## Configuração de Assinaturas
- Criação de diferentes tipos de assinaturas
- Atribuição a grupos de gerenciamento específicos

## Organização por Regiões
- Seleção de regiões primárias e secundárias
- Configuração de pares de região para DR

## Criação de Grupos de Recursos

Criei o meu grupo de recursos em EAST US, a título de experimentação, pois irei criar uma VNet no Brasil.

# Passo 3: Documentação e Boas Práticas
- Criação de política de nomenclatura
- Implementação de tags para rastreabilidade
- Configuração de políticas de segurança
- Documentação da arquitetura

# Links Úteis
Documentação Oficial Microsoft

- [Visão geral da arquitetura do Azure](https://learn.microsoft.com/pt-br/azure/architecture/guide/)
- [Pares de região do Azure](https://learn.microsoft.com/pt-br/azure/reliability/regions-paired)
- [Grupos de gerenciamento do Azure](https://learn.microsoft.com/pt-br/azure/governance/management-groups/overview)
- [Grupos de recursos do Azure](https://learn.microsoft.com/pt-br/azure/azure-resource-manager/management/manage-resource-groups-portal)

Ferramentas e Recursos
- [Calculadora de preços do Azure](https://azure.microsoft.com/pt-br/pricing/calculator/)
- [Centro de Arquitetura do Azure](https://learn.microsoft.com/pt-br/azure/architecture/)
- [Introdução à Infraestrutura de Nuvem: Descrever conceitos de nuvem](https://learn.microsoft.com/pt-br/training/paths/microsoft-azure-fundamentals-describe-cloud-concepts/)
