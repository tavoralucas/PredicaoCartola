# Predicao para uso no Cartola ou Apostas no Brasileirão Serie A - 2025

O projeto PredicaoCartola tem como objetivo analisar dados estatísticos de confrontos e scouts de jogadores do Campeonato Brasileiro para sugerir apostas, escalações e estratégias com maior potencial de sucesso no fantasy game Cartola FC. Utilizando probabilidades de resultados, desempenho dos times como mandante/visitante e scouts individuais dos jogadores, o sistema auxilia o usuário a tomar decisões mais embasadas para cada rodada.

## Legenda das Siglas

- **PVM**: Probabilidade de Vitória do Mandante
- **PE**: Probabilidade de Empate
- **PVV**: Probabilidade de Vitória do Visitante
- **PEM**: Probabilidade de Empate do Mandante
- **PDM**: Probabilidade de Derrota do Mandante
- **PEV**: Probabilidade de Empate do Visitante
- **PDV**: Probabilidade de Derrota do Visitante

## Estrutura dos Dados

- `probabilidade_confronto`: Probabilidades de resultado para cada confronto da rodada.
- `probabilidade_time.json`: Probabilidades detalhadas de desempenho de cada time, como mandante e visitante.
- `cartola_scouts_defesa.json` e `cartola_scouts_ataque.json`: Scouts individuais dos jogadores, separados por defesa e ataque.
- `CONFRONTOS/`: Histórico de confrontos por rodada.

## Como Utilizar

1. **Preparação dos Dados:**
   - Certifique-se de que os arquivos de scouts e probabilidades estejam atualizados para a rodada desejada.
2. **Execução da Análise:**
   - Utilize os scripts ou notebooks do projeto para gerar análises, sugestões de apostas e escalações.
3. **Interpretação dos Resultados:**
   - Consulte as probabilidades e scouts para embasar suas decisões no Cartola FC ou em apostas esportivas.

## Público-Alvo

- Jogadores do Cartola FC que buscam melhorar seu desempenho.
- Apostadores que desejam embasar suas escolhas em dados estatísticos.
- Analistas de dados esportivos interessados em futebol brasileiro.
