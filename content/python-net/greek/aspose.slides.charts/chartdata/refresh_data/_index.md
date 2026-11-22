---
title: refresh_data method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/refresh_data/
weight: 30
---
## refresh_data(self) {#}
Ανανεώνει τα δεδομένα του διαγράμματος επαναφορτώνοντας τα από το αρχικό βιβλίο εργασίας.

```python
def refresh_data(self):
    ...
```

### Παρατηρήσεις
Εάν το διάγραμμα χρησιμοποιεί εξωτερικό βιβλίο εργασίας, το βιβλίο εργασίας πρέπει να είναι προσβάσιμο τη στιγμή της κλήσης.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Εκτοξεύεται όταν η μορφή του βιβλίου εργασίας δεν υποστηρίζεται, ή όταν [`ChartData.data_source_type`](/slides/python-net/el/aspose.slides.charts/chartdata/data_source_type) είναι<br/>            [`ChartDataSourceType.EXTERNAL_WORKBOOK`](/slides/python-net/el/aspose.slides.charts/chartdatasourcetype/EXTERNAL_WORKBOOK) και το εξωτερικό βιβλίο εργασίας δεν μπορεί να προσπελαστεί ή να φορτωθεί. |

### Δείτε επίσης
* κλάση [`ChartData`](/slides/python-net/el/aspose.slides.charts/chartdata)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)