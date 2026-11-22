---
title: set_range method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.charts/chartdata/set_range/
weight: 50
---
## set_range(self, formula) {#str}
Ορίστε το εύρος δεδομένων του διαγράμματος. Series and categories θα ενημερωθούν βάσει του νέου εύρος δεδομένων.
Αν ο αριθμός των series στο εύρος δεδομένων είναι μεγαλύτερος από τον αριθμό των series στα δεδομένα του διαγράμματος, τότε πρόσθετες series με τον ίδιο τύπο όπως το τελευταίο series στην τρέχουσα συλλογή θα προστεθούν στο τέλος της συλλογής.

```python
def set_range(self, formula):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| formula | **str** | Η formula εύρους δεδομένων των κελιών. Π.χ: "Sheet1!$A$1:$C$4" , "SomeSheetName!A1:B100", "Sheet1!$A$1:$B$5;Sheet1!$D$1:$D$5". |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | Η formula είναι None. |
| **RuntimeError(Proxy error(InvalidOperationException))** | Μη υποστηριζόμενος τύπος διαγράμματος |
| **RuntimeError(Proxy error(ArgumentException))** | Η formula έχει εσφαλμένη μορφή. |

### Δείτε επίσης
* κλάση [`ChartData`](/slides/python-net/el/aspose.slides.charts/chartdata)
* μονάδα [`aspose.slides.charts`](/slides/python-net/el/aspose.slides.charts)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)