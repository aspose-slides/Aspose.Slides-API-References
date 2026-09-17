---
title: check_write_protection method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/iprotectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Καθορίζει αν μια παρουσίαση είναι προστατευμένη κωδικός πρόσβασης για τροποποίηση.

### Επιστρέφει

True if the password is valid; otherwise, false.



```python
def check_write_protection(self, password):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| password | **str** | Ο κωδικός πρόσβασης για έλεγχο. |

### Παρατηρήσεις

1. Θα πρέπει να ελέγξετε την ιδιότητα [`IProtectionManager.is_write_protected`](/slides/python-net/el/aspose.slides/iprotectionmanager/is_write_protected) πριν καλέσετε αυτή τη μέθοδο.
2. Όταν ο κωδικός πρόσβασης είναι None ή κενός, αυτή η μέθοδος επιστρέφει false.



### Δείτε επίσης
* κλάση [`IProtectionManager`](/slides/python-net/el/aspose.slides/iprotectionmanager)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)