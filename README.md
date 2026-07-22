# CBSI — Gestão Operacional v15 (Obra Vale ES · Porto de Tubarão)

Sistema de gestão operacional do contrato CBSI × VALE ES (Pintura Industrial e Cobertura — Contrato 5900117444 · CC CB803480).

**Acesso:** abra o `index.html` publicado (GitHub Pages). Login com usuário e senha (padrão inicial: 1234 — altere no primeiro acesso).

## Novidades desta versão (evolução sobre a v15 FINAL 58)

- 🤖 **Robô de Ponto** (aba Espelho Ponto): lê o Espelho do Cartão de Ponto em PDF (com OCR de reserva para PDF escaneado), cruza com o cadastro de Efetivos (ID → Matrícula CBSI → Função), aplica o De×Para de funções CBSI → funções cobradas (QQP), consolida HN / HE 50% / HE 100% / HE 150% / AD. Noturno, exporta Excel com fórmulas, imprime e replica automaticamente nos itens HH do Boletim de Medição (com desfazer).
- ☁️ **Atualização de dados manual e automática**: upload manual sempre disponível; leitura automática de pastas do Google Drive quando compartilhadas como "qualquer pessoa com o link" + chave de API do Google.
- 🏗️ **Aba Projetos Andaimes**: controle de projetos de andaimes com status, responsáveis e leitura da pasta do Drive.

Nenhum módulo anterior foi alterado ou removido — as 20 abas originais da v15 (58) estão preservadas.

## Arquivos

- `index.html` — o sistema completo (arquivo único)
- `pdf.min.js`, `pdf.worker.min.js`, `xlsx.full.min.js` — bibliotecas locais (usadas quando o CDN estiver bloqueado na rede)

## Observação de privacidade

O sistema contém dados de colaboradores. O login protege a interface, mas o repositório é público — avalie manter o repositório privado se necessário.
