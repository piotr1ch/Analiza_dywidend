# Analiza dywidend

## Opis projektu

Repozytorium zawiera projekty związane z analizą dywidend spółek notowanych na warszawskiej giełdzie (GPW).  
Celem jest gromadzenie danych historycznych o dywidendach oraz umożliwienie ich analizy w celu podejmowania lepszych decyzji inwestycyjnych.

## Foldery i projekty

### 1_Power_Query
Projekt w Excelu wykorzystujący **Power Query**, który automatyzuje proces pobierania danych z serwisu [strefa inwestorów](https://strefainwestorow.pl/).  
Skoroszyt gromadzi informacje o spółkach notowanych na GPW, które od 2000 roku prowadziły politykę dywidendową.  
Dzięki Power Query arkusz umożliwia szybkie i efektywne pobieranie oraz przetwarzanie danych, co ułatwia śledzenie historii dywidendowej spółek.
Efektem jest szereg wskaźników przedstawiających regularność i jakość wypłat.
[Zobacz szczegóły projektu (README.md)](/1_Power_Query/README.md)

### 2_Power_BI

![Page1](2_Power_BI/assets/Page1.png)

Projekt w Power BI wykorzystuje dane pozyskane z wcześniejszego projektu (1_Power_Query), dodatkowo rozszerza je o użycie **DAX** w celu uproszczenia obliczeń.  

Celem jest przeliczenie wszystkich wskaźników wcześniej obliczanych w Power Query, co służy nauce DAX. Następnie uzyskane wskaźniki zostaną **znormalizowane i zwizualizowane w dashboardzie**, umożliwiając analizę dywidend spółek notowanych na GPW.  
[Zobacz szczegóły projektu (README.md)](/2_Power_BI/README.md)