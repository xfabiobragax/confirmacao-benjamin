# Formulário de Confirmação de Presença - Festa do Benjamin

## Descrição
Este é um formulário web criativo e esteticamente bonito para confirmação de presença na festa de 1 ano do Benjamin. O design segue o tema visual do convite com balões de ar quente, nuvens e uma paleta de cores em tons azuis e cinza.

## Características
- **Design Responsivo**: Funciona perfeitamente em desktop e dispositivos móveis
- **Animações Suaves**: Elementos animados como nuvens flutuantes e balões
- **Interatividade**: Efeitos visuais nos campos e botões
- **Validação**: Validação de campos obrigatórios
- **Modal de Confirmação**: Feedback visual bonito após o envio
- **Tema Personalizado**: Cores e elementos visuais que combinam com o convite

## Campos do Formulário
1. **Nome Completo** (obrigatório)
2. **Confirmação de Presença** (obrigatório)
   - Sim, estarei presente! 🎉
   - Não poderei comparecer 😔
3. **Observações** (opcional) - Para restrições alimentares, mensagens especiais, etc.

## Como Usar

### Opção 1: Servidor Local
1. Abra o terminal na pasta do projeto
2. Execute: `python3 -m http.server 8000`
3. Acesse: `http://localhost:8000`

### Opção 2: Hospedagem Web
1. Faça upload dos arquivos (`index.html`, `styles.css`, `script.js`) para seu servidor web
2. Acesse o arquivo `index.html` através do navegador

## Arquivos Inclusos
- `index.html` - Estrutura principal do formulário
- `styles.css` - Estilos e animações
- `script.js` - Funcionalidades interativas
- `README.md` - Este arquivo de instruções

## Funcionalidades Técnicas
- **Armazenamento Local**: As respostas são salvas no localStorage do navegador para demonstração
- **Animações CSS**: Efeitos visuais suaves e profissionais
- **JavaScript Vanilla**: Sem dependências externas
- **Responsividade**: Media queries para diferentes tamanhos de tela

## Personalização
Para personalizar o formulário:
1. **Cores**: Edite as variáveis CSS no arquivo `styles.css`
2. **Textos**: Modifique o conteúdo no arquivo `index.html`
3. **Funcionalidades**: Ajuste o comportamento no arquivo `script.js`

## Integração com Backend
Para integrar com um sistema de backend real:
1. Modifique a função `saveRSVP()` no arquivo `script.js`
2. Substitua o localStorage por uma chamada AJAX/fetch para sua API
3. Configure o endpoint de destino para receber os dados do formulário

## Suporte
O formulário foi testado e funciona em:
- Chrome, Firefox, Safari, Edge
- Dispositivos desktop e móveis
- Diferentes resoluções de tela

---

**Criado especialmente para a festa de 1 ano do Benjamin! 🎈**

