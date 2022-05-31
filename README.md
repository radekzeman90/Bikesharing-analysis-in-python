# Analýza bikesharingu v Edinburghu / Bikesharing analysis in Edinburgh - Python (pandas)

Projekt v tomto repozitáři je jedním ze dvou výstupů kurzu datové analýzy od společnosti Engeto, který jsem absolvoval mezi zářím 2021 a lednem 2022. Kód je psán v jazyce Python. Jedná se o analýzu projektu bikesharingu v Edinburgu. Tato analýza čerpá data z databáze výpůjček analyzovaného projektu (stanice, kde bylo kolo půjčeno a vráceno spolu i časovým záznamem, zeměpisné souřadnice stanic) a z databáze počasí v Edinburgu (teplota, srážky, vítr, vlhkost atd. měřeny v 3hodinových intervalech).  Výstupy mají grafickou, popř. tabulkovou podobu a jsou v zásadě tyto:

- Identifikace stanic bikesharingu, které jsou aktivní/neaktivní, nejvytíženější, s nejvíce přebývajícími/chybějícími koly.
- Určení vzdálenosti mezi stanicemi.
- Průměrná doba výpůjčky a grafické zobrazení počtu výpůjček podle doby vypůjčení.
- Zobrazení vývoje počtu výpůjček ve sledovaném období.
- Určení faktorů ovlivňující půjčování kol, např. počasí.
- Zodpovězení otázky, zda si lidé půjčují kola více o víkendu nebo v pracovním týdnu.

Projekt je psán v Jupyter notebooku a jeho výstupy jsou viditelné i bez spuštění kódu.
//////

Project in this repository is one of the two outputs of Data analytics academy of Engeto company, which I completede in january 2022. Code is written in Python. The purpose of the program is analysis of bikesharing project in Edinburgh. The source of data for this project is a database including information like origin and end station with timestamps, latitude and longitude of stations etc. and also meteorological data of weather in Edinburg (temperature, rain, wind speed, humudity atc. measured in 3 hour intervals). Outputs are in tables and graphs:

- Bikeshrarin station evaluation - active/inactive, the most used, with most bikes missing/redundant.
- Determing the distance between stations.
- Avarage rent time and graph of rent count by rent time.
- Graph of evolution of rent count in evaluated perio
- Determination of key factors that affects bike renting, e.g. weather.
- Answering question, wheather people rent bikes more on weekdays or on weekends.

Project is written in Jupyter notebook and its outputs are visible without launching the code.

