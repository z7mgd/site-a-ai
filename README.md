# Central do Açaí

Loja virtual de uma página só para a Central do Açaí: cardápio ilustrado, montador de açaí em 5 passos, copos da felicidade, milkshake, açaí de garrafa e picolés. O pedido sai pronto no WhatsApp da loja.

## Como usar

É um único arquivo, sem instalação nem build. Abra `index.html` no navegador ou publique em qualquer hospedagem estática (GitHub Pages, Netlify, Vercel).

## O que o site faz

- Montador de açaí em 5 passos (tamanho, sabor, condimentos, cobertura, extras), com limite de 4 condimentos e copo que muda ao vivo
- Itens do cardápio personalizáveis: tamanho, tirar ou adicionar ingredientes e observação
- Carrinho com quantidade, retirada ou entrega e nome, salvo no navegador por 12 horas
- Mensagem do WhatsApp organizada e pronta para enviar
- Funciona no celular e acompanha o tema claro ou escuro do aparelho

## Onde editar

Tudo fica dentro de `index.html`, no bloco `<script>`:

| O que mudar | Onde |
| --- | --- |
| Número do WhatsApp | `PHONE` e `PHONE_TXT`, no começo do script |
| Horário de funcionamento (liga o selo aberto/fechado) | `HOURS`, logo abaixo do número |
| Sabores, preços e tamanhos | `PRODUCTS` e as listas de sabores acima dele |
| Condimentos e coberturas | `COND_L` e `COB_L` |
| Instagram | link `@central_do_acai_rj` na seção de contato |

Os valores e a disponibilidade são confirmados pela loja no WhatsApp. Sabores, preços e textos devem ser conferidos com a loja antes de publicar.
