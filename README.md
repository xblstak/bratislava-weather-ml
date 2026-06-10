# Predikcia počasia pomocou strojového učenia

Projekt je zameraný na analýzu historických meteorologických dát a vytváranie modelov strojového učenia na predikciu a klasifikáciu počasia.

## Cieľ projektu

Hlavným cieľom bolo spracovať meteorologické dáta, analyzovať ich vlastnosti a vytvoriť modely schopné predikovať vybrané meteorologické veličiny alebo klasifikovať poveternostné podmienky.

## Zdroj dát

Použité boli historické údaje z meteorologickej stanice Bratislava získané prostredníctvom knižnice Meteostat.

Obdobie:

- 2022 – 2025

Dáta obsahujú napríklad:

- teplotu vzduchu,
- relatívnu vlhkosť,
- zrážky,
- rýchlosť vetra,
- smer vetra,
- atmosférický tlak,
- meteorologické podmienky.

## Použité technológie

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Meteostat

## Postup riešenia

### Príprava dát

- získanie dát z externého zdroja,
- odstránenie nepotrebných atribútov,
- spracovanie chýbajúcich hodnôt,
- kontrola kvality dát.

### Analýza dát

- základné štatistiky,
- vizualizácie,
- identifikácia trendov a vzťahov medzi premennými.

### Regresné modely

Na predikciu numerických hodnôt bol použitý:

- Linear Regression

Vyhodnotenie modelu:

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- R² Score

### Klasifikačné modely

Na klasifikáciu poveternostných podmienok boli použité:

- Decision Tree Classifier
- Random Forest Classifier

Vyhodnotenie modelov:

- Accuracy
- Precision
- Recall
- Confusion Matrix

## Výsledok

Projekt demonštruje kompletný proces tvorby modelov strojového učenia od získania dát až po vyhodnotenie úspešnosti modelov. Zároveň ukazuje praktické využitie knižnice Scikit-learn pri riešení regresných a klasifikačných úloh.
