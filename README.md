# FrostMap

FrostMap é uma aplicação web interativa que visualiza ocorrências de geadas no Brasil, auxiliando agricultores, meteorologistas e entusiastas do clima a monitorar condições de geada.

## Descrição

O FrostMap exibe eventos de geada em um mapa interativo do Brasil, classificando-os por intensidade com base nos dados de temperatura:
- **Geada forte**: temperaturas abaixo de -5°C (marcadores vermelhos)
- **Geada moderada**: temperaturas entre -5°C e 0°C (marcadores amarelos)
- **Geada fraca**: temperaturas acima de 0°C (marcadores azuis)

A aplicação fornece informações detalhadas sobre cada ocorrência de geada, incluindo localização, data e temperatura mínima através de tooltips interativos e popups.

## Tecnologias Utilizadas

- **Leaflet.js**: Biblioteca de mapeamento interativo usada para renderizar o mapa e marcadores
- **HTML5/CSS3**: Estrutura e estilização da aplicação
- **JavaScript**: Lógica da aplicação e processamento de dados
- **Tailwind CSS**: Framework CSS utilitário para estilização de componentes
- **Wicket**: Biblioteca para manipulação de dados WKT (Well-Known Text) para o contorno do Brasil
- **JSON**: Formato de armazenamento de dados para registros de geada

## Funcionalidades

- Mapa interativo mostrando ocorrências de geada no Brasil
- Marcadores codificados por cores indicando intensidade da geada
- Tooltips mostrando informações básicas ao passar o mouse
- Popups detalhados com dados da geada ao clicar nos marcadores
- Legenda explicando o sistema de codificação por cores
- Design responsivo

## Estrutura do Projeto

- `index.html`: Página principal da aplicação
- `script.js`: Lógica da aplicação para manipulação do mapa e dados
- `styles.css`: Estilos CSS para a interface do usuário
- `geadas.json` e `geadas-jun-23.json`: Dados de ocorrências de geada
- `dados.json`: Informações sobre municípios do Brasil
- Arquivos de ícones: `marker-icon-blue.png`, `marker-icon-red.png`, `marker-icon-yellow.png`

## Melhorias Futuras

- Múltiplas ocorrências por cidade
- Capacidades de filtragem
- Visualização baseada em período
- Informações meteorológicas mais detalhadas

## Como Usar

1. Clone ou baixe este repositório
2. Abra o arquivo `index.html` em um navegador web
3. Interaja com o mapa para ver detalhes sobre as ocorrências de geada