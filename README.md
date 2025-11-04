# Poster Minimal

## Descrição
Modelo simples de cartaz 1080×1350 focado em tipografia e contraste, personalizável via variáveis CSS, pensado para eventos e anúncios rápidos, evitando a cor verde para manter consistência visual.  
Inclui um template HTML/CSS minimalista e instruções para editar título, subtítulo, data/local e chamada para ação, com exportação em PNG/PDF via navegador.

## Instalação
- Pré-requisitos: navegador moderno (Chrome/Firefox/Edge), sem dependências extras.  
- Clone este repositório: `git clone https://github.com/passatempoxd/Poster-Minimal.git`  
- Abra `design/poster.html` no navegador  
- Edite textos no HTML e cores em `design/styles.css` conforme necessário

## Uso
- Edite os campos no `<header>` de `design/poster.html` para título e subtítulo e, em seguida, atualize a seção de informações (data/local/CTA).  
- Ajuste as variáveis CSS em `design/styles.css` para personalização rápida:

```
:root{
--brand:#1E3A8A; /* azul-escuro /
--accent:#F97316; / laranja /
--ink:#111827; / grafite /
--bg:#FAFAFA; / fundo claro */
}
```

- Exporte o cartaz:  
- Captura de tela em alta resolução  
- Ou “Imprimir” > “Salvar como PDF” com margens mínimas

## Contribuindo
- Faça um fork, crie uma branch `feat/<sua-feature>`, faça commits com mensagens claras e abra um Pull Request explicando motivação e passos de teste.  
- Preserve a hierarquia tipográfica e o contraste AA; evite introduzir a cor verde para manter a identidade do exemplo.

## Licença
MIT — Uso livre para fins educacionais e comerciais; inclua o aviso de copyright.
