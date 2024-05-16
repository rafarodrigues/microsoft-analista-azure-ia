# Análise de Aluguéis de Bicicletas - Modelos de Regressão
<br>
<img src="https://github.com/rafarodrigues/microsoft-analista-azure-ia/blob/53cf1831d887cbcaad03cfc35b61cb0cd6b90938/regressao-em-python/dados/header.jpg?raw=true" width="700" alt="exemplo imagem">

> Este código contém a análise para a aplicação do dataset de aluguéis de bicicletas (bike-rentals) utilizando diversos modelos de regressão, tanto localmente quanto na nuvem através do Azure Machine Learning.

## Sobre o Projeto

O objetivo deste projeto é comparar a precisão de diversos modelos de regressão aplicados ao dataset de aluguéis de bicicletas. O código foi desenvolvido para servir como um parâmetro de conferência entre a execução manual e a execução diretamente na nuvem utilizando o Azure Machine Learning.

## Link para o projeto

<a href="https://github.com/rafarodrigues/microsoft-analista-azure-ia/blob/main/regressao-em-python/Regress%C3%A3o-em-python-bike_rentals.ipynb" target="_blank">microsoft-analista-azure-ia/regressao-em-python
/Regressão-em-python-bike_rentals.ipynb</a>


## Tecnologias Utilizadas

Este projeto foi construído com as seguintes tecnologias e bibliotecas:

- [Python](https://www.python.org/)
- [NumPy](https://numpy.org/)
- Pandas
- [Matplotlib](https://matplotlib.org/)
- Seaborn
- Scikit-Learn
- [XGBoost](https://xgboost.readthedocs.io/en/latest/)
- [LightGBM](https://lightgbm.readthedocs.io/en/latest/)
- [Microsoft Azure Machine Learning](https://azure.microsoft.com/en-us/services/machine-learning/)

## Projeto

Para rodar este projeto localmente, siga as instruções abaixo.

### Dependências

Instale as seguintes bibliotecas:

>  sh
> `conda install -c conda-forge numpy pandas matplotlib seaborn scikit-learn xgboost lightgbm`

### Resumo

O notebook inclui a leitura do dataset, pré-processamento, treino dos modelos, e avaliação dos resultados.

| ID | Regressor                 | R-squared  | Mean Squared Error |
|----|---------------------------|------------|--------------------|
| 6  | ExtraTreesRegressor       | 78.686.995 | 0.154456           |
| 1  | GradientBoostingRegressor | 76.420.638 | 0.170880           |
| 4  | SGDRegressor              | 75.566.424 | 0.177071           |
| 5  | RandomForestRegressor     | 74.567.340 | 0.184311           |
| 8  | XGBRegressor              | 74.498.237 | 0.184812           |
| 3  | KNeighborsRegressor       | 73.977.869 | 0.188583           |
| 7  | LGBMRegressor             | 72.908.080 | 0.196336           |
| 2  | DecisionTreeRegressor     | 54.479.847 | 0.329886           |
| 0  | ElasticNet                | 16.957.668 | 0.601810           |

## Roadmap

- [x]  Leitura e análise inicial dos dados
- [x]  Treinamento e avaliação de múltiplos modelos de regressão
- [ ]  Implementação de novos modelos
- [ ]  Otimização de hiperparâmetros

## Licença

Distribuído sob a licença MIT.

## Autores

- Rafael Rodrigues - [@rafarodrigues](https://github.com/rafarodrigues)

Link do Projeto: [https://github.com/seu_usuario/nome_do_projeto](https://github.com/seu_usuario/nome_do_projeto)