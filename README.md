# Análise de Queimadas no Brasil

Este projeto realiza uma análise das queimadas no Brasil utilizando dados do Instituto Nacional de Pesquisas Espaciais (INPE). Os dados foram obtidos através do TerraBrasilis, uma plataforma que fornece informações sobre focos de queimadas em território nacional. A apuração foi feita com a base de dados de 2024 inteira até o dia de hoje.

## Principais Análises:
1. **Queimadas por Mês**
   - **Código:** `count_burns_by_month`
   - **Descrição:** Conta o número de queimadas por mês e calcula estatísticas como somatório, média e desvio padrão usando NumPy.
   - **Visualização:** Gráfico de barras mostrando o número de queimadas por mês.

2. **Queimadas por Estado**
   - **Código:** `count_burns_by_state`
   - **Descrição:** Conta o número de focos de queimadas por estado.
   - **Visualização:** Gráfico de barras mostrando o número de focos por estado.

3. **Queimadas por Município**
   - **Código:** `count_burns_by_municipality`
   - **Descrição:** Conta o número de focos de queimadas por município e exibe os 10 municípios com mais focos.
   - **Visualização:** Gráfico de barras mostrando o número de focos por município.

4. **Tendência de Queimadas**
   - **Código:** `predict_future_burns`
   - **Descrição:** Calcula a média móvel das queimadas diárias e utiliza regressão linear para prever queimadas futuras.
   - **Visualização:** Gráfico mostrando a tendência de queimadas, incluindo previsões para os próximos 30 dias.

5. **Média do FRP por Bioma**
   - **Código:** `calculate_mean_frp_by_biome`
   - **Descrição:** Calcula a média do FRP para diferentes biomas.
   - **Visualização:** Gráfico de barras mostrando a média do FRP por bioma.

## Como Executar
- Clone este repositório.
- Instale as dependências necessárias: `pip install pandas numpy matplotlib seaborn scikit-learn`.
- Execute os scripts Python na ordem desejada.

## Tecnologias Utilizadas:
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Contribuições
Sinta-se à vontade para contribuir com melhorias ou sugestões!

Os dados utilizados neste projeto foram obtidos do INPE através do TerraBrasilis.
