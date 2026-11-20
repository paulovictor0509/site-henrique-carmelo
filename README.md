# Site do Dr. Henrique Carmelo

Site de apresentação do médico Henrique Carmelo (CRM-SP 239996).
Consultas on-line, por vídeo.

- `index.html`: o site inteiro (textos, estilo e animações)
- `assets/`: logo HC e fotos tratadas

Para ativar o WhatsApp, edite a linha `const WHATSAPP = ""` no `index.html` com o número (DDI + DDD, só dígitos).

## Conteúdos (blog)
Os textos ficam na lista `POSTS` dentro do `index.html`. Para publicar um texto novo, basta pedir ao Claude: ele escreve, o Henrique aprova e o texto entra no topo da lista.

### Agendamento de textos
Textos com data futura ficam escondidos e aparecem sozinhos no dia. Para revisar todos antes, abra o site com `#previa` no fim do endereço (e `#previa-off` para voltar ao normal).
