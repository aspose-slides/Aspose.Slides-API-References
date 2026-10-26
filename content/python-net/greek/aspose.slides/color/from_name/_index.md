---
title: from_name method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/color/from_name/
weight: 40
---
## from_name(name) {#str}
Δημιουργεί ένα χρώμα από το συγκεκριμένο όνομα ενός προκαθορισμένου χρώματος.<br/>Η αναζήτηση δεν διακρίνει μεταξύ πεζών και κεφαλαίων και αγνοεί τις υπογραμμίσεις και τα κενά: `"LightBlue"`, `"lightblue"` και `"light_blue"` όλα αντιστοιχούν στο `Color.light_blue`. Δείτε τη σελίδα κλάσης [`Color`](/slides/python-net/el/aspose.slides/color) για τη λίστα των προκαθορισμένων χρωμάτων.

### Επιστρέφει

Το ονομαστικό χρώμα.



```python
@staticmethod
def from_name(name):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| name | **str** | Μια συμβολοσειρά που είναι το όνομα ενός προκαθορισμένου χρώματος. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **ValueError** | Το όνομα δεν είναι όνομα ενός προκαθορισμένου χρώματος. |
| **TypeError** | Το όνομα δεν είναι συμβολοσειρά. |



### Δείτε επίσης
* κλάση [`Color`](/slides/python-net/el/aspose.slides/color)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)