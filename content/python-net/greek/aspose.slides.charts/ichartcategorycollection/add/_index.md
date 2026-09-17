---
title: add method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides.charts/ichartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Αν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά δημιουργεί νέα κατηγορία διαγράμματος από 
            [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) και την προσθέτει στη συλλογή.

### Επιστρέφει

Προστέθηκε ή υπάρχουσα κατηγορία.

```python
def add(self, chart_data_cell):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) | Κελί που χρησιμοποιείται για τη δημιουργία κατηγορίας διαγράμματος. |

## add(self, value) {#any}
Δημιουργεί νέο [`IChartCategory`](/slides/python-net/el/aspose.slides.charts/ichartcategory) από την τιμή και το προσθέτει στη συλλογή.

### Επιστρέφει

Προστέθηκε [`IChartCategory`](/slides/python-net/el/aspose.slides.charts/ichartcategory).

```python
def add(self, value):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| value | **any** | Η τιμή. |

### Παρατηρήσεις

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί.  Εάν χρησιμοποιείτε [`IChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/ichartdataworkbook) για να προσθέσετε ή να επεξεργαστείτε τιμές κελιών, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας
            Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | αν ξεπεραστεί το όριο |

### Δείτε επίσης
* κλάση [`IChartCategory`](/slides/python-net/el/aspose.slides.charts/ichartcategory)
* κλάση [`IChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/ichartcategorycollection)
* κλάση [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell)
* κλάση [`IChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/ichartdataworkbook)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)