---
title: add method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chartseriescollection/add/
weight: 10
---
## add(self, type) {#charttype}
Δημιουργεί νέα σειρά γραφήματος και την προσθέτει στη συλλογή.

### Επιστρέφει

Νέα σειρά γραφήματος.



```python
def add(self, type):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype) | Type of series |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Δημιουργεί νέα σειρά γραφήματος από [`ChartDataCell`](/slides/python-net/el/aspose.slides.charts/chartdatacell) και την προσθέτει στη συλλογή.

### Επιστρέφει

Η σειρά γραφήματος που προστέθηκε ή η σειρά που ήδη υπάρχει στη συλλογή.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) | Cell which contain series name. |
| type | [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype) | Type set type of series |

### Παρατηρήσεις

Εάν η σειρά γραφήματος δημιουργηθεί από το ίδιο κελί που υπάρχει ήδη στη συλλογή, η μέθοδος δεν προσθέτει τίποτα και επιστρέφει τον δείκτη της.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Δημιουργεί νέα σειρά γραφήματος από [`ChartCellCollection`](/slides/python-net/el/aspose.slides.charts/chartcellcollection) και την προσθέτει στη συλλογή.

### Επιστρέφει

Η σειρά γραφήματος που προστέθηκε ή η σειρά που ήδη υπάρχει στη συλλογή.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/el/aspose.slides.charts/ichartcellcollection) | Cells which contain series name. |
| type | [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype) | Type set type of series |

### Παρατηρήσεις

Εάν η σειρά γραφήματος δημιουργηθεί από το ίδιο κελί που υπάρχει ήδη στη συλλογή, η μέθοδος δεν προσθέτει τίποτα και επιστρέφει τον δείκτη της.


## add(self, name, type) {#str-charttype}
Δημιουργεί νέα σειρά γραφήματος από τιμή και την προσθέτει στη συλλογή.

### Επιστρέφει

Η σειρά γραφήματος που προστέθηκε.



```python
def add(self, name, type):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | **str** | Series name. |
| type | [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype) | Type set type of series |



### Δείτε επίσης
* κλάση [`ChartCellCollection`](/slides/python-net/el/aspose.slides.charts/chartcellcollection)
* κλάση [`ChartDataCell`](/slides/python-net/el/aspose.slides.charts/chartdatacell)
* κλάση [`ChartSeriesCollection`](/slides/python-net/el/aspose.slides.charts/chartseriescollection)
* απαρίθμηση [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype)
* κλάση [`IChartCellCollection`](/slides/python-net/el/aspose.slides.charts/ichartcellcollection)
* κλάση [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell)
* κλάση [`IChartSeries`](/slides/python-net/el/aspose.slides.charts/ichartseries)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)