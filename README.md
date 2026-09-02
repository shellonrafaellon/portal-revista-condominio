# Portal Revista Condomínio

Portal editorial da **Revista Condomínio** — jornalismo especializado no mercado condominial brasileiro.

Site estático, sem build. Basta servir a pasta.

## Páginas

| Arquivo | Página |
| --- | --- |
| `index.html` | Entrada (redireciona para a home) |
| `Revista Condominio.dc.html` | Home do portal |
| `Noticias.dc.html` | Listagem de notícias (filtro por editoria + busca) |
| `Materia.dc.html` | Página interna de matéria |
| `Guia Comercial.dc.html` | Guia de fornecedores + pedido de orçamento |
| `Revista Digital.dc.html` | Leitor online e acervo de edições |
| `Anuncie.dc.html` | Mídia kit, formatos de banner e planos |
| `Institucional.dc.html` | Quem somos, expediente, privacidade, termos |

`support.js` é o runtime das páginas e `uploads/revista.png` é o logotipo — ambos obrigatórios.

## Rodar localmente

```bash
python3 -m http.server 8000
# abra http://localhost:8000
```

## Publicar no GitHub Pages

Settings → Pages → Source: `Deploy from a branch` → branch `main`, pasta `/ (root)`.

## Identidade

- Azul-marinho `#102A43` · Verde-esmeralda `#00A86B` · Dourado `#D4A72C` · Cinza-claro `#F5F7FA`
- Manchetes em Source Serif 4; textos em Archivo
