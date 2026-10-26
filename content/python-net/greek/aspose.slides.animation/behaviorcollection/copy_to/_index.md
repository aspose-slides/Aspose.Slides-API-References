---
title: copy_to method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides.animation/behaviorcollection/copy_to/
weight: 40
---
## copy_to(self, array, array_index) {#listibehavior-int}
Αντιγράφει τα στοιχεία της **System.Collections.Generic.ICollection`1** σε ένα **System.Array**, ξεκινώντας από ένα συγκεκριμένο δείκτη **System.Array**.

```python
def copy_to(self, array, array_index):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| array | **List[IBehavior]** | Το μονοδιάστατο **System.Array** που είναι ο προορισμός των στοιχείων που αντιγράφονται από **System.Collections.Generic.ICollection`1**. Το **System.Array** πρέπει να έχει μηδενική δεικτοδότηση. |
| array_index | **int** | Ο μηδενικός δείκτης στο `array` από τον οποίο ξεκινά η αντιγραφή. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` είναι μικρότερο του 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Ο αριθμός των στοιχείων στην πηγή **System.Collections.Generic.ICollection`1** είναι μεγαλύτερος από τον διαθέσιμο χώρο από το `array_index` μέχρι το τέλος του προορισμού `array`. |

### Δείτε επίσης
* κλάση [`BehaviorCollection`](/slides/python-net/el/aspose.slides.animation/behaviorcollection)
* μονάδα [`aspose.slides.animation`](/slides/python-net/el/aspose.slides.animation)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)