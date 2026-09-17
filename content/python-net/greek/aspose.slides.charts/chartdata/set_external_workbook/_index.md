---
title: set_external_workbook method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/set_external_workbook/
weight: 30
---
## set_external_workbook(self, workbook_path) {#str}
Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα. Τα δεδομένα του γραφήματος θα ενημερωθούν από το βιβλίο εργασίας-στόχο.

```python
def set_external_workbook(self, workbook_path):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| workbook_path | **str** | Διαδρομή προς το βιβλίο εργασίας-στόχο |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Το εξωτερικό βιβλίο εργασίας δεν είναι διαθέσιμο ή δεν μπορεί να φορτωθεί. |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το γράφημα.

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| workbook_path | **str** | Διαδρομή προς το βιβλίο εργασίας-στόχο |
| update_chart_data | **bool** | Εάν η τιμή είναι ψευδής, θα ενημερωθεί μόνο η διαδρομή του βιβλίου εργασίας. <br/><br/>             Τα δεδομένα του γραφήματος δεν θα φορτωθούν και δεν θα ενημερωθούν από το βιβλίο εργασίας-στόχο. Μπορεί να χρησιμοποιηθεί όταν το βιβλίο εργασίας-στόχο δεν υπάρχει ή δεν είναι διαθέσιμο.<br/><br/>             Εάν η τιμή είναι αληθής, τα δεδομένα του γραφήματος θα ενημερωθούν από το βιβλίο εργασίας-στόχο. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Το εξωτερικό βιβλίο εργασίας δεν είναι διαθέσιμο ή δεν μπορεί να φορτωθεί. |

### Δείτε επίσης
* κλάση [`ChartData`](/slides/python-net/el/aspose.slides.charts/chartdata)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)