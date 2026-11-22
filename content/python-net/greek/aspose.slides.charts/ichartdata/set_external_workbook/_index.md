---
title: set_external_workbook method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.charts/ichartdata/set_external_workbook/
weight: 40
---
## set_external_workbook(self, workbook_path) {#str}
Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα. Τα δεδομένα του διαγράμματος θα ενημερωθούν από το στοχευόμενο βιβλίο εργασίας.

```python
def set_external_workbook(self, workbook_path):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Διαδρομή προς το στοχευόμενο βιβλίο εργασίας |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Το εξωτερικό βιβλίο εργασίας δεν είναι διαθέσιμο ή δεν μπορεί να φορτωθεί. |

## set_external_workbook(self, workbook_path, update_chart_data) {#str-bool}
Ορίζει εξωτερικό βιβλίο εργασίας ως πηγή δεδομένων για το διάγραμμα.

```python
def set_external_workbook(self, workbook_path, update_chart_data):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| workbook_path | **str** | Διαδρομή προς το στοχευόμενο βιβλίο εργασίας |
| update_chart_data | **bool** | Εάν η τιμή είναι ψευδής, μόνο η διαδρομή του βιβλίου εργασίας θα ενημερωθεί. <br/><br/>             Τα δεδομένα του διαγράμματος δεν θα φορτωθούν και δεν θα ενημερωθούν από το στοχευόμενο βιβλίο εργασίας. Μπορεί να χρησιμοποιηθεί όταν το στοχευμένο βιβλίο εργασίας δεν υπάρχει ή δεν είναι διαθέσιμο.<br/><br/>             Εάν η τιμή είναι αληθής, τα δεδομένα του διαγράμματος θα ενημερωθούν από το στοχευόμενο βιβλίο εργασίας. |

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Το εξωτερικό βιβλίο εργασίας δεν είναι διαθέσιμο ή δεν μπορεί να φορτωθεί. |

### Δείτε επίσης
* κλάση [`IChartData`](/slides/python-net/el/aspose.slides.charts/ichartdata)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)