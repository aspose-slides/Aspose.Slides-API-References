---
title: copy_to method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/paragraphcollection/copy_to/
weight: 50
---
## copy_to(self, array, array_index) {#listiparagraph-int}
Αντιγράφει τα στοιχεία του **System.Collections.Generic.ICollection`1** σε ένα **System.Array**, ξεκινώντας από ένα συγκεκριμένο δείκτη **System.Array**.

```python
def copy_to(self, array, array_index):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| array | **List[IParagraph]** | Το μονοδιάστατο **System.Array** που είναι ο προορισμός των στοιχείων που αντιγράφονται από **System.Collections.Generic.ICollection`1**. Το **System.Array** πρέπει να έχει μηδενική αρίθμηση. |
| array_index | **int** | Ο δείκτης μηδενικής βάσης στο `array` όπου αρχίζει η αντιγραφή. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | `array` είναι None. |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | `array_index` είναι μικρότερο του 0. |
| **RuntimeError(Proxy error(ArgumentException))** | Ο αριθμός των στοιχείων στην πηγή **System.Collections.Generic.ICollection`1** είναι μεγαλύτερος από το διαθέσιμο χώρο από το `array_index` μέχρι το τέλος του προορισμού `array`. |

### Δείτε επίσης
* κλάση [`ParagraphCollection`](/slides/python-net/el/aspose.slides/paragraphcollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)