# Segurança e privacidade

O `index.html` distribuído aqui executa uma demonstração local. A configuração padrão não contém tokens nem chave de mapas e não se conecta aos sistemas de produção.

Para uma integração futura:

- Faça autenticação e autorização no servidor; não publique credenciais ou tokens permanentes no HTML.
- Exponha à interface apenas os dados necessários ao operador autorizado.
- Colete localização somente de dispositivos autorizados, com finalidade, retenção e acesso definidos.
- Evite inserir detalhes de falhas exploráveis, informações pessoais ou segredos em issues públicas. Procure o mantenedor por um canal privado para relatos sensíveis.
- Não trate o estado visual dos módulos como prova de disponibilidade de serviços não instrumentados.

Este repositório não implementa o servidor nem políticas de acesso a dados reais.
