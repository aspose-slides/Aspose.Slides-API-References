---
title: set_external_workbook method
second_title: Aspose.Slides dla Pythona via .NET – Dokumentacja API
description: 
type: docs
url: /pl/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. Dane wykresu zostaną zaktualizowane z docelowego skoroszytu.


```python
def set_external_workbook(self, workbook_path):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| workbook_path | **str** | Ścieżka do docelowego skoroszytu |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Zewnętrzny skoroszyt jest niedostępny lub nie można go załadować. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| workbook_path | **str** | Ścieżka do docelowego skoroszytu |
| update_chart_data | **bool** | Jeśli wartość jest fałsz, zostanie zaktualizowana tylko ścieżka do skoroszytu. <br/><br/>             Dane wykresu nie będą wczytywane i aktualizowane z docelowego skoroszytu. Może być użyte, gdy docelowy skoroszyt nie istnieje lub nie jest dostępny.<br/><br/>             Jeśli wartość jest prawda, dane wykresu zostaną zaktualizowane z docelowego skoroszytu. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Zewnętrzny skoroszyt jest niedostępny lub nie można go załadować. |



### Zobacz także
* klasa [`ChartData`](/slides/python-net/pl/aspose.slides.charts/chartdata)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)