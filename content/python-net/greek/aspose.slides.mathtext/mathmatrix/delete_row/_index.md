---
title: delete_row method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides.mathtext/mathmatrix/delete_row/
weight: 50
---
## delete_row(self, row_index) {#int}
Διαγράφει τη συγκεκριμένη γραμμή


```python
def delete_row(self, row_index):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| row_index | **int** | Ο δείκτης μηδενικής βάσης της γραμμής προς διαγραφή. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(InvalidOperationException))** | Όταν προσπαθείτε να διαγράψετε την τελευταία μοναδική γραμμή στον πίνακα |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Εάν rowIndex μικρότερο του μηδενός ή μεγαλύτερο ή ίσο με το RowCount |



### Δείτε επίσης
* κλάση [`MathMatrix`](/slides/python-net/el/aspose.slides.mathtext/mathmatrix)
* μονάδα [`aspose.slides.mathtext`](/slides/python-net/el/aspose.slides.mathtext)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)