---
title: set_range method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/set_range/
weight: 40
---
## set_range(self, formula) {#str}
Ορίστε το εύρος δεδομένων του διαγράμματος. Οι σειρές και οι κατηγορίες θα ενημερωθούν με βάση το νέο εύρος δεδομένων.
Εάν ο αριθμός των σειρών στο εύρος δεδομένων είναι μεγαλύτερος από τον αριθμό των σειρών στα δεδομένα του διαγράμματος, τότε θα προστεθούν επιπλέον σειρές με τον ίδιο τύπο όπως η τελευταία σειρά στην τρέχουσα συλλογή, στο τέλος της συλλογής.

```python
def set_range(self, formula):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| formula | **str** | Ο τύπος της περιοχής δεδομένων των κελιών. Π.χ: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | η formula είναι None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Μη υποστηριζόμενος τύπος διαγράμματος |
| **RuntimeError(Proxy error(ArgumentException))** | η formula έχει εσφαλμένη μορφή. |



### Δείτε επίσης
* κλάση [`ChartData`](/slides/python-net/el/aspose.slides.charts/chartdata)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)