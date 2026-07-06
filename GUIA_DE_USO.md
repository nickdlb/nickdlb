# Guia rápido para publicar o perfil GitHub de Nícolas Dias

## 1. Crie o repositório especial

No GitHub, crie um repositório público chamado exatamente:

```txt
nickdlb
```

Como seu usuário é `nickdlb`, o repositório também precisa se chamar `nickdlb` para o README aparecer no seu perfil.

## 2. Envie os arquivos

Envie para a raiz do repositório:

- `README.md`
- `assets/banner.svg`
- `.github/workflows/generate-snake.yml`, se quiser a animação de contribuições
- `.github/workflows/blog-post.yml`, se tiver um blog/RSS para listar posts

## 3. Ajustes recomendados

No `README.md`, substitua quando tiver:

- `SEU_EMAIL`
- `SEU_LINKEDIN`
- `SEU_PORTFOLIO`
- links dos projetos Feedybacky, LicitaAi, LocalSEO e outros projetos

## 4. Ative a automação da cobrinha

Depois do primeiro commit, vá em:

`Settings > Actions > General > Workflow permissions`

Ative permissão de escrita para workflows, se essa opção aparecer. O arquivo `generate-snake.yml` já inclui `permissions: contents: write`.

## 5. Primeiro commit sugerido

```bash
git add .
git commit -m "Create GitHub profile README"
git push origin main
```

## 6. Próximos upgrades

- Adicionar links reais dos projetos.
- Criar uma versão em inglês do README.
- Adicionar prints, demos ou links de produção.
- Criar uma seção “Cases” com problemas resolvidos, impacto e stack usada.
