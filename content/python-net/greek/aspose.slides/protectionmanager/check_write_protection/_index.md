---
title: check_write_protection method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/protectionmanager/check_write_protection/
weight: 10
---
## check_write_protection(self, password) {#str}
Καθορίζει εάν μια παρουσίαση είναι προστατευμένη με κωδικό πρόσβασης για τροποποίηση.

### Επιστρέφει
True εάν ο κωδικός πρόσβασης είναι έγκυρος· αλλιώς, false.

```python
def check_write_protection(self, password):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| password | **str** | Ο κωδικός πρόσβασης για έλεγχο. |

### Παρατηρήσεις
1. Θα πρέπει να ελέγξετε την ιδιότητα [`ProtectionManager.is_write_protected`](/slides/python-net/el/aspose.slides/protectionmanager/is_write_protected) πριν καλέσετε αυτή τη μέθοδο.
2. Όταν ο κωδικός πρόσβασης είναι None ή κενός, αυτή η μέθοδος επιστρέφει false.

### Δείτε επίσης
* κλάση [`ProtectionManager`](/slides/python-net/el/aspose.slides/protectionmanager)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)