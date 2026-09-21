# Cronômetro — apresentação

Versão de apresentação do Cronômetro, separada do ambiente pessoal de desenvolvimento.

## Ambientes

- `stable`: versão oficial de apresentação.
- `development`: versão beta de apresentação.
- `main`: pacote público servido pelo GitHub Pages.

A versão oficial e a beta de apresentação são mantidas separadas das versões de uso pessoal.

## Regra de produto — sem Áreas

A versão de apresentação não expõe o conceito de Áreas.

- Não existe seletor, cadastro, edição, exclusão ou configuração de Áreas na interface.
- Não existe modo genérico de cronômetro sem cliente/atendimento como ambiente alternativo.
- O aplicativo funciona sempre no contexto de atendimentos e clientes.
- O diretório/cadastro de clientes fica sempre disponível.
- Modelos, atendimentos, registros, clientes e estatísticas usam um único escopo lógico.
- Se for necessário manter um identificador interno de área por compatibilidade técnica ou importação de dados, ele deve ser fixo e invisível ao usuário, sem comportamento de múltiplas áreas.
- Importações de estruturas antigas com várias áreas devem ser normalizadas para esse único escopo da apresentação, preservando os dados relevantes.
