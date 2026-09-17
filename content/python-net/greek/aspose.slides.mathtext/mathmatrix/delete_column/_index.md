---
title: delete_column method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides.mathtext/mathmatrix/delete_column/
weight: 40
---
## delete_column(self, column_index) {#int}
Διαγράφει τη συγκεκριμένη στήλη


```python
def delete_column(self, column_index):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| column_index | **int** | Ο μηδενικός δείκτης της στήλης προς διαγραφή. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Όταν προσπαθείτε να διαγράψετε την τελευταία μοναδική στήλη στον πίνακα |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Εάν το columnIndex είναι μικρότερο του μηδενός ή μεγαλύτερο ή ίσο με το ColumnCount |



### Δείτε επίσης
* κλάση [`MathMatrix`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)