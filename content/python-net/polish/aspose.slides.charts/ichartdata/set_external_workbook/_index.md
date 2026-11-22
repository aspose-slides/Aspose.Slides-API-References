---
title: set_external_workbook method
second_title: Aspose.Slides dla Pythona przez .NET API
description: 
type: docs
url: /pl/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu. Dane wykresu będą aktualizowane z docelowego skoroszytu.


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
| **RuntimeError(Proxy error(InvalidOperationException))** | Zewnętrzny skoroszyt nie jest dostępny lub nie można go załadować. |


## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Ustawia zewnętrzny skoroszyt jako źródło danych dla wykresu.


```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| workbook_path | **str** | Ścieżka do docelowego skoroszytu |
| update_chart_data | **bool** | Jeśli wartość jest false, tylko ścieżka do skoroszytu zostanie zaktualizowana. <br/><br/>             Dane wykresu nie będą ładowane i aktualizowane z docelowego skoroszytu. Może być użyte, gdy docelowy skoroszyt nie istnieje lub nie jest dostępny.<br/><br/>             Jeśli wartość jest true, dane wykresu zostaną zaktualizowane z docelowego skoroszytu. |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Zewnętrzny skoroszyt nie jest dostępny lub nie można go załadować. |



### Zobacz także
* klasa [`IChartData`](/slides/python-net/pl/aspose.slides.charts/ichartdata)
* moduł [`aspose.slides.charts`](/slides/python-net/pl/aspose.slides.charts)
* biblioteka [`Aspose.Slides`](/slides/python-net)