# Estimador de Área por Monte Carlo

Aplicação web estática para estimar áreas pelo método de Monte Carlo.

## Recursos
- Retângulo e círculo com comparação ao valor analítico.
- Polígono desenhado pelo usuário.
- Quantidade configurável de amostras.
- Visualização dos pontos amostrados.
- Estimativa de área e erro relativo quando existe valor analítico.

## Como usar
Abra a aplicação publicada ou o arquivo `index.html`. Não requer backend, banco de dados ou dependências externas.

## Fórmula
A estimativa é:

`A_estimativa = (pontos dentro / pontos totais) × área da caixa envolvente`

Para retângulo e círculo, o software também calcula o erro relativo em relação à área analítica conhecida.

## GitHub Pages
O workflow em `.github/workflows/pages.yml` publica automaticamente o conteúdo do repositório no GitHub Pages quando o Pages estiver habilitado para o repositório.
