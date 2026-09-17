---
title: add method
second_title: Aspose.Slides για Python μέσω .NET API
description: 
type: docs
url: /el/aspose.slides.charts/chartcellcollection/add/
weight: 10
---
## add(self, cell) {#ichartdatacell}
Προσθέτει νέο κελί στη συλλογή.

```python
def add(self, cell):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| cell | [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) | Νέο κελί για προσθήκη. |

## add(self, value) {#any}
Δημιουργεί [`ChartDataCell`](/slides/python-net/el/aspose.slides.charts/chartdatacell) από την καθορισμένη τιμή και το προσθέτει στη συλλογή.

```python
def add(self, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | **any** | Η τιμή. |

### Παρατηρήσεις

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί.  Εάν χρησιμοποιείτε [`ChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/chartdataworkbook) για να προσθέσετε ή να επεξεργαστείτε τιμές Cell, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας
            Το μέγιστο αριθμό τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | εάν ξεπεραστεί το όριο |



### Δείτε επίσης
* κλάση [`ChartCellCollection`](/slides/python-net/el/aspose.slides.charts/chartcellcollection)
* κλάση [`ChartDataCell`](/slides/python-net/el/aspose.slides.charts/chartdatacell)
* κλάση [`ChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/chartdataworkbook)
* κλάση [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)