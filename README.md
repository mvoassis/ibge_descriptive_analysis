# IBGE Descriptive Analysis
## Marcos V. O. Assis (mvoassis@gmail.com)

### National Household Sample Survey - Brazil - 2015

The <b>National Household Sample Survey - 2015</b> annually investigates, on a permanent basis, general characteristics of the population, education, work, income, housing, and others, with variable frequency, according to the information needs for the country, such as characteristics on migration, fertility, marriage, health, food security, among other topics. The survey of these statistics constitutes, over the 49 years of the research, an important instrument for the formulation, validation and evaluation of policies oriented towards socioeconomic development and the improvement of living conditions in Brazil.

### Data Source

https://ww2.ibge.gov.br/home/estatistica/populacao/trabalhoerendimento/pnad2015/microdados.shtm

### Variáveis utilizadas

> ### Income (Renda)
> ***

Monthly income from main work for persons aged 10 years and over.

> ### Age (Idade)
> ***

Age of the resident at the reference date in years.

> ### Height (Altura) (own elaboration)
> ***

Height of resident in meters. Constructed under normal distribution for testing. 

> ### State (UF)
> ***

|Code|Description|
|---|---|
|11|Rondônia|
|12|Acre|
|13|Amazonas|
|14|Roraima|
|15|Pará|
|16|Amapá|
|17|Tocantins|
|21|Maranhão|
|22|Piauí|
|23|Ceará|
|24|Rio Grande do Norte|
|25|Paraíba|
|26|Pernambuco|
|27|Alagoas|
|28|Sergipe|
|29|Bahia|
|31|Minas Gerais|
|32|Espírito Santo|
|33|Rio de Janeiro|
|35|São Paulo|
|41|Paraná|
|42|Santa Catarina|
|43|Rio Grande do Sul|
|50|Mato Grosso do Sul|
|51|Mato Grosso|
|52|Goiás|
|53|Distrito Federal|

> ### Sex (Sexo)	
> ***

|Code|Description|
|---|---|
|0|Male|
|1|Female|

> ### Years of Study (Anos de Estudo)
> ***

|Code|Description|
|---|---|
|1|No education and less than 1 year|
|2|1 year|
|3|2 years|
|4|3 years|
|5|4 years|
|6|5 years|
|7|6 years|
|8|7 years|
|9|8 years|
|10|9 years|
|11|10 years|
|12|11 years|
|13|12 years|
|14|13 years|
|15|14 years|
|16|15 years or more|
|17|Not determined| 
||Not applicable|

> ### Color (Cor)
> ***

|Código|Descrição|
|---|---|
|0|Indigenous|
|2|White|
|4|Black|
|6|Yellow|
|8|Brown|
|9|No declaration|

#### <font color='red'>Note</font>
***

> The following treatments were performed on the original data:
> 1. The records where the <b>Income</b> was invalid (999 999 999 999) were eliminated;
> 2. The records where the <b>Income</b> was missing were eliminated;
> 3. Only the records of the <b>Reference Persons</b> of each household (responsible for the household) were considered.
