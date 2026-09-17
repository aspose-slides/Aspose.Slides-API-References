---
title: check_write_protection method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ipresentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Ελέγχει εάν ένας κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση με προστασία εγγραφής.

### Επιστρέφει

Αληθές εάν η παρουσίαση είναι προστατευμένη από εγγραφή και ο κωδικός πρόσβασης είναι σωστός. Ψευδές διαφορετικά.



```python
def check_write_protection(self, password):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| password | **str** | Ο κωδικός πρόσβασης προς έλεγχο. |

### Παρατηρήσεις

1. Θα πρέπει να ελέγξετε την ιδιότητα [`IPresentationInfo.is_write_protected`](/slides/python-net/el/aspose.slides/ipresentationinfo/is_write_protected) πριν καλέσετε αυτή τη μέθοδο.
2. Όταν ο κωδικός πρόσβασης είναι None ή κενός, αυτή η μέθοδος επιστρέφει ψευδές.

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Δείτε επίσης
* κλάση [`IPresentationInfo`](/slides/python-net/el/aspose.slides/ipresentationinfo)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)