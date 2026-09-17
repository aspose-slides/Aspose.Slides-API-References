---
title: check_write_protection method
second_title: Aspose.Slides για Python μέσω .NET - Αναφορά API
description: 
type: docs
url: /el/aspose.slides/presentationinfo/check_write_protection/
weight: 20
---
## check_write_protection(self, password) {#str}
Ελέγχει εάν ένας κωδικός πρόσβασης για τροποποίηση είναι σωστός για μια παρουσίαση με προστασία εγγραφής.

### Επιστρέφει

True αν η παρουσίαση είναι προστατευμένη από εγγραφή και ο κωδικός πρόσβασης είναι σωστός. False διαφορετικά.



```python
def check_write_protection(self, password):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| password | **str** | Ο κωδικός πρόσβασης προς έλεγχο. |

### Παρατηρήσεις

1. Θα πρέπει να ελέγξετε την ιδιότητα [`PresentationInfo.is_write_protected`](/slides/python-net/el/aspose.slides/presentationinfo/is_write_protected) πριν καλέσετε αυτή τη μέθοδο.
2. Όταν ο κωδικός πρόσβασης είναι None ή κενός, αυτή η μέθοδος επιστρέφει false.

### Εξαιρέσεις

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** |  |



### Δείτε επίσης
* κλάση [`PresentationInfo`](/slides/python-net/el/aspose.slides/presentationinfo)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)