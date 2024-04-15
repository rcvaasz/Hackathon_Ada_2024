# Nome dos Integrantes

💡 [Eduardo Silva Carvalho](https://github.com/educarvallho)  
💡 [Isabella Cristina Arving](https://github.com/IsabellaArving)  
💡 [Leonardo Henrique de Brito Junior](https://github.com/LeonardoHBritoo)  
💡 [Luiz Antonio C O Junior](https://github.com/luizolijr)  
💡 [Michael Santana](https://github.com/michaelsantana95)  
💡 [Raphael Cleber Vaz](https://github.com/rcvaasz)  
💡 [Ricardo Mazzeo](https://github.com/rtmazzeo)  
💡 [Vitor Guilherme de Sousa Fontenele](https://github.com/fontenelevitor)  
💡 [Wiliams Alves](https://github.com/alves05)

# Hackathon Ada Tech 2024

Análise e Melhorias de Práticas para Diversidade e Inclusão Social na empresa fictícia CORP SOLUTIONS

# Proposta

Desenvolver uma análise visando entender a dinâmica atual da empresa na questão de diversidade e inclusão social de Pessoas com Deficiência (PcD) e oferecer soluções para a empresa trilhe um caminho para se tornar mais diversa e inclusa.
Para a realização das análises foi utilizado uma base de dados disponibilizada pela empresa, os dados remetem as características dos colaboradores no âmbito da empresa, as variáveis disponibilizadas na base para analise são o gênero, idade, raça, educação, endereço, estado, tempo de casa, departamento e senioridade.

## Práticas do desenvolvimento do projeto

- Coleta da base de dados usando python
- Tratamento de encoding e strings com auxilio do python
- Tratamento dos dados aplicado com python
- Exploração dos dados, utilizando gráficos e tabelas em python
- Utilização do Power BI para análise e insghts
- Apresentação de problemas e proposta de solução

## Informações do Conjunto de Dados  

O conjunto de dados inclui as seguintes colunas:  

- `ID`: ID do funcionário;
- `Nome`: Nome do funcionário;
- `Gênero`: Gênero do funcionário;
- `Idade`: Idade do funcionário;
- `Raça`: Raça do funcionário;
- `Formação`: Nível de educação do funcionário;
- `Endereço`: Endereço do funcionário;
- `Estado`: Estado do funcionário;
- `Tempo de Casa`: Tempo de permanência do funcionário na empresa;
- `Departamento`: Departamento onde o funcionário trabalha;
- `Senioridade`: Nível de senioridade do funcionário.

## Limpeza e Preparação dos Dados  

- Removida a segunda coluna 'id';
- Renomeadas as colunas para melhor legibilidade;
- Reordenadas as colunas;
- Padronizadas as categorias de gênero;
- Capitalizadas as categorias de raça;
- Capitalizadas as categorias de educação;
- Padronizadas as categorias de senioridade;
- Substituído '\r\n' por ';' na coluna 'Endereço';
- Substituído ',' por ';' na coluna 'Endereço';
- Convertidas as colunas 'Idade' e 'Tempo de Casa' para o tipo inteiro.  

## Visualização  

O projeto inclui visualização de várias distribuições no conjunto de dados:  

- Histograma da distribuição de idade;
- Gráfico de pizza mostrando a distribuição de gênero;
- Gráfico de barras mostrando a distribuição de raça;
- Gráfico de barras mostrando a distribuição de educação;
- Gráfico de barras mostrando a distribuição de estado;
- Gráfico de barras mostrando a distribuição de região;
- Gráfico de barras mostrando a distribuição de departamento;
- Gráfico de barras mostrando a distribuição de senioridade;
- Histograma da distribuição de tempo de casa.

## Dashboard
- Filtro de funcionários entre Feminino e Masculino;
- Filtro de funcionários por cor/raça;
- Contagem de identificações;
- Distribuição por gênero (Gráfico de pizza);
- Distribuição por raça (Gráfico de barras);
- Distribuição de raça por cargos (Gráfico de barras empilhadas 100%);
- Distribuição por raça (Gráfico de colunas);
- Distribuição de idades por sexo (Gráfico de colunas).

## Ferramentas e Bibliotecas  

O projeto foi implementado usando as seguintes ferramentas e bibliotecas:

- `Python`
- `PowerBI`
- `Canva`
- `Pandas`
- `os`
- `Requests`
- `Matplotlib`
- `Seaborn`
- `Dashboard`
- `GeoPandas`
- `Requests`
- `ftfy`

## Como Usar  

- Clone este repositório para sua máquina local;
- Execute o arquivo Jupyter Notebook para explorar o conjunto de dados e as visualizações;
- Abra o dashbord_corp_solution.pbix para checar o Painel Final e alguns insights iniciais.
