---
title: copy_to method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/portioncollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listiportion-int}
Αντιγράφει τα στοιχεία του **System.Collections.Generic.ICollection`1** σε ένα **System.Array**, ξεκινώντας από ένα συγκεκριμένο δείκτη **System.Array**.

```python
def copy_to(self, array, array_index):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| array | **List[IPortion]** | Ο μονοδιάστατος **System.Array** που είναι ο προορισμός των αντιγραμμένων στοιχείων από **System.Collections.Generic.ICollection`1**. Ο **System.Array** πρέπει να έχει μηδενική αρίθμηση. |
| array_index | **int** | Ο μηδενικός δείκτης στο `array` από τον οποίο αρχίζει η αντιγραφή. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` είναι μικρότερο από 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Ο αριθμός των στοιχείων στην πηγή **System.Collections.Generic.ICollection`1** είναι μεγαλύτερος από τον διαθέσιμο χώρο από `array_index` μέχρι το τέλος του προορισμού `array`. |

### Δείτε επίσης
* κλάση [`PortionCollection`](/slides/python-net/el/aspose.slides/portioncollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)