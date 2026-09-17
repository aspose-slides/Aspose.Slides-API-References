---
title: add method
second_title: Αναφορά API του Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.charts/chartcategorycollection/add/
weight: 10
---
## add(self, chart_data_cell) {#ichartdatacell}
Αν η κατηγορία υπάρχει στη συλλογή, την επιστρέφει. Διαφορετικά δημιουργεί νέα κατηγορία διαγράμματος από 
[`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) και την προσθέτει στη συλλογή.

### Επιστρέφει

Προστιθέμενη ή υπάρχουσα κατηγορία.



```python
def add(self, chart_data_cell):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| chart_data_cell | [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell) | Κελί που χρησιμοποιείται για τη δημιουργία κατηγορίας διαγράμματος. |


## add(self, value) {#any}
Δημιουργεί νέο [`ChartCategory`](/slides/python-net/el/aspose.slides.charts/chartcategory) από την τιμή και το προσθέτει στη συλλογή.

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

Αυτή η μέθοδος προσθέτει φύλλο εργασίας με όνομα AUTO_DATA και προσθέτει όλες τις τιμές εκεί.  Εάν χρησιμοποιείτε [`ChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/chartdataworkbook) για προσθήκη ή επεξεργασία τιμών κελιών, βεβαιωθείτε ότι δεν χρησιμοποιείτε αυτό το φύλλο εργασίας
            Ο μέγιστος αριθμός τιμών που προστίθενται με αυτή τη μέθοδο δεν πρέπει να υπερβαίνει το 16711680

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | εάν υπερβεί το όριο |



### Δείτε επίσης
* κλάση [`ChartCategory`](/slides/python-net/el/aspose.slides.charts/chartcategory)
* κλάση [`ChartCategoryCollection`](/slides/python-net/el/aspose.slides.charts/chartcategorycollection)
* κλάση [`ChartDataWorkbook`](/slides/python-net/el/aspose.slides.charts/chartdataworkbook)
* κλάση [`IChartCategory`](/slides/python-net/el/aspose.slides.charts/ichartcategory)
* κλάση [`IChartDataCell`](/slides/python-net/el/aspose.slides.charts/ichartdatacell)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)