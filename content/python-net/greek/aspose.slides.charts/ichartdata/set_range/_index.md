---
title: set_range method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.charts/ichartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Ορίστε την περιοχή δεδομένων του διαγράμματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν με βάση τη νέα περιοχή δεδομένων.
Αν ο αριθμός των σειρών στην περιοχή δεδομένων είναι μεγαλύτερος από τον αριθμό σειρών στα δεδομένα του διαγράμματος, τότε επιπλέον σειρές με τον ίδιο τύπο με την τελευταία σειρά στην τρέχουσα συλλογή θα προστεθούν στο τέλος της συλλογής.

```python
def set_range(self, formula):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| formula | **str** | Ο τύπος περιοχής δεδομένων των κελιών. Π.χ: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Το formula είναι None. |
| **RuntimeError(Proxy error(ArgumentException))** | Το formula έχει εσφαλμένη μορφή. |

### Δείτε επίσης
* κλάση [`IChartData`](/slides/python-net/el/aspose.slides.charts/ichartdata)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)