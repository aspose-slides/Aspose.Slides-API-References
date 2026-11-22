---
title: refresh_data method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides.charts/ichartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Ανανεώνει τα δεδομένα του διαγράμματος επαναφορτώνοντας τα από το αρχείο εργασίας προέλευσης.


```python
def refresh_data(self):
    ...
```


### Παρατηρήσεις

Αν το διάγραμμα χρησιμοποιεί εξωτερικό αρχείο εργασίας, το αρχείο εργασίας πρέπει να είναι προσβάσιμο τη στιγμή της κλήσης.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Εξέγερση όταν η μορφή του αρχείου εργασίας δεν υποστηρίζεται, ή όταν [`IChartData.data_source_type`](/slides/python-net/el/aspose.slides.charts/ichartdata/data_source_type) είναι<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/el/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) και το εξωτερικό αρχείο εργασίας δεν μπορεί να προσπελαστεί ή να φορτωθεί. |



### Δείτε επίσης
* κλάση [`IChartData`](/slides/python-net/el/aspose.slides.charts/ichartdata)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)