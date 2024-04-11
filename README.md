# Bem-vindo(a) ao meu Portfólio de Data Analytics e Data Science

[![author](https://img.shields.io/badge/alexandre-pereira-2202bb11a.svg)](https://www.linkedin.com/in/alexandre-pereira-2202bb11a/) ![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)

<p align="center">
  <img src="https://miro.medium.com/v2/resize:fit:870/1*14v1pUZwr516557dpS-oYw.jpeg" width=85%>
</p>

## **PROJETOS**

## **Data Science**

### [**Estudo Sobre Violência Policial nos EUA - Kaggle**](https://github.com/pereira-alexandre/Data-Science-Police-violence)

- **Data Wrangling de exploração de um dataset de diferentes fontes sobre violência policial nos EUA**, em que foram realizadas questionamentos sobre a correlação de descriminação recial nas ocorrências.
- Para obter os dados: consumi os dados do site Kaggle com a biblioteca pandas, e fiz todas as perguntas e cruzamentos para obter insights.
- [Fonte dos Dados](https://www.kaggle.com/amark720/police-killings)
- [Acesse o Notebook](https://github.com/pereira-alexandre/Data-Science-Police-violence/blob/main/Viol%C3%AAncia_policial.ipynb)
- [Leia a Matéria](https://agenciabrasil.ebc.com.br/internacional/noticia/2021-06/onu-pede-fim-de-impunidade-da-violencia-policial-contra-negros)

<p align="center">
  <img alt="BA" width="90%" src="assets\img\Estatisticas.png">
</p>


### [**Crawler Comparador de Preços - Carnes em Mercados**](https://github.com/pereira-alexandre/Web-Crawler-Compare-Prices)

- **Um Bot Crawler projetado para navegar automaticamente pelos sites, extrair dados específicos e armazená-los em formato estruturado para posterior análise**.

- **Web Crawling:** O código começa importando a biblioteca Scrapy e definindo um spider Scrapy chamado PriceMeatBot. Este spider é responsável por rastrear URLs específicos e extrair dados deles. Nesse caso, as URLs pertencem aos sites de dois mercados de carne, Super Nosso e Angeloni. O spider faz isso enviando solicitações HTTP para esses URLs e processando as respostas para extrair os dados necessários.
<p align="left">
  <img alt="BA" width="30%" src="assets\img\ScrapyImage.png">
</p>


- **Data Extraction:** O método de análise na classe PriceMeatBot é onde ocorre a extração de dados real. Ele usa seletores CSS para direcionar partes específicas do código HTML e extrair os dados relevantes. Isso inclui o nome, o preço e a unidade dos diferentes tipos de carne disponíveis nos sites do mercado.
<p align="left">
  <img alt="BA" width="30%" src="assets\img\ScrapyImageCssSelector.png">
</p>

- **Data Storage:** Após extrair os dados, o script os armazena em arquivos JSON. Isso é feito usando o módulo json integrado do Python. Os dados são então carregados em DataFrames do pandas para análise posterior.
- **[Acesse meu estudo para conferir na integra!](https://github.com/pereira-alexandre/Web-Crawler-Compare-Prices)**

<img src="https://lordicon.com/icons/wired/flat/1320-json.gif" width="430" height="300"/>



## **Algoritmos**

### [**Validador De CPF**](https://github.com/pereira-alexandre/cpf-document-validator)

- **Algoritmo, documentando didaticamente com o racional de uma validação de CPF**, no qual teve o foco em instruir futuaras implementações em outras ferramentas ou sistemas complexos.
- Implementado em Python no paradigma de Orientação a Objeto para fácil interpretação e refatoração futura.
- [Acesse o Documento](https://github.com/pereira-alexandre/cpf-document-validator)
- [Clique aqui para obter mais detalhes do código fonte](https://github.com/pereira-alexandre/cpf-document-validator/blob/main/cpf_validator.py)

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExbG0xM3pzNTlsbTdqazJkdTBiZGpwcGNvdXNyaGNiaWdrcnl5cjNnNyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/cNy35I5u02gljOO2Qw/giphy.gif" width="600" height="530"/>

## **BI**

### [**Análise de COVID19**](https://github.com/pereira-alexandre/Covid-Dashboard)
- **Dashboard interativo com dados públicos a nível Brasil e mundo**, aqui foi feita uma análise com estatística descritiva sobre óbitos, infecções e regiões mais afetadas pela doença, bem como seu impacto econômico do período.

<p align="center">
  <img alt="BA" width="40%" src="https://raw.githubusercontent.com/pereira-alexandre/Covid-Dashboard/main/img/Resume.gif">
</p>


