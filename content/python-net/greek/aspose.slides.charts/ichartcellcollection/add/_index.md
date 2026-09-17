---
title: add method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.charts/ichartcellcollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Προσθέτει νέο κελί στη συλλογή.


```python
def add(self, chart_data_cell):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) | Νέο κελί προς προσθήκη. |


## add(self, value) {#any}
Δημιουργεί [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) από την καθορισμένη τιμή και το προσθέτει στη συλλογή.


```python
def add(self, value):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | **any** | Η τιμή. |

### Σχόλια

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με το όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί.  Εάν χρησιμοποιείτε [`IChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/ichartdataworkbook) για προσθήκη ή επεξεργασία τιμών Cell, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας
            Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | εάν υπερβεί το όριο |



### Δείτε επίσης
* κλάση [`IChartCellCollection`](/slides/python-net/el/aspose.slides.charts/ichartcellcollection)
* κλάση [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell)
* κλάση [`IChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/ichartdataworkbook)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)