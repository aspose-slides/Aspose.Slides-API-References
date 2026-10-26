---
title: add method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/ichartseriescollection/add/
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
| type | [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype) | Τύπος σειράς |


## add(self, cell_with_series_name, type) {#ichartdatacell-charttype}
Δημιουργεί νέα σειρά γραφήματος από [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) και την προσθέτει στη συλλογή.

### Επιστρέφει

Προστέθηκε σειρά γραφήματος ή σειρά που ήδη υπάρχει στη συλλογή.



```python
def add(self, cell_with_series_name, type):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cell_with_series_name | [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) | Κελί που περιέχει το όνομα της σειράς. |
| type | [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype) | Ορίζει τον τύπο της σειράς |

### Παρατηρήσεις

Αν η σειρά γραφήματος δημιουργηθεί από το ίδιο κελί που ήδη υπάρχει στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το δείκτη της.


## add(self, cells_with_series_name, type) {#ichartcellcollection-charttype}
Δημιουργεί νέα σειρά γραφήματος από [`IChartCellCollection`](/slides/python-net/el/aspose.slides.charts/ichartcellcollection) και την προσθέτει στη συλλογή.

### Επιστρέφει

Προστέθηκε σειρά γραφήματος ή σειρά που ήδη υπάρχει στη συλλογή.



```python
def add(self, cells_with_series_name, type):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cells_with_series_name | [`IChartCellCollection`](/slides/python-net/el/aspose.slides.charts/ichartcellcollection) | Κελιά που περιέχουν το όνομα της σειράς. |
| type | [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype) | Ορίζει τον τύπο της σειράς |

### Παρατηρήσεις

Αν η σειρά γραφήματος δημιουργηθεί από το ίδιο κελί που ήδη υπάρχει στη συλλογή, τότε η μέθοδος δεν προσθέτει τίποτα και επιστρέφει το δείκτη της.


## add(self, name, type) {#str-charttype}
Δημιουργεί νέα σειρά γραφήματος από τιμή και την προσθέτει στη συλλογή.

### Επιστρέφει

Προστέθηκε σειρά γραφήματος.



```python
def add(self, name, type):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | **str** | Όνομα σειράς. |
| type | [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype) | Ορίζει τον τύπο της σειράς |



### Δείτε επίσης
* απαρίθμηση [`ChartType`](/slides/python-net/el/aspose.slides.charts/charttype)
* κλάση [`IChartCellCollection`](/slides/python-net/el/aspose.slides.charts/ichartcellcollection)
* κλάση [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell)
* κλάση [`IChartSeries`](/slides/python-net/el/aspose.slides.charts/ichartseries)
* κλάση [`IChartSeriesCollection`](/slides/python-net/el/aspose.slides.charts/ichartseriescollection)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)