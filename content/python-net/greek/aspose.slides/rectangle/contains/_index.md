---
title: contains method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/rectangle/contains/
weight: 20
---
## contains(self, point) {#point}
Καθορίζει εάν το συγκεκριμένο σημείο βρίσκεται μέσα σε αυτό το ορθογώνιο.

### Επιστρέφει

`True` if the point is contained within this rectangle; otherwise, `False`.



```python
def contains(self, point):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [`Point`](/slides/python-net/el/aspose.slides/point) | Το σημείο προς δοκιμή. Δέχεται οποιοδήποτε αντικείμενο με ιδιότητες `x` και `y`. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, rect) {#rectangle}
Καθορίζει εάν η περιοχή του ορθογωνίου που εκπροσωπείται από `rect` περιέχεται εξ ολοκλήρου μέσα σε αυτό το ορθογώνιο.

### Επιστρέφει

`True` if the rectangular region represented by `rect` is entirely contained within this rectangle; otherwise, `False`.



```python
def contains(self, rect):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [`Rectangle`](/slides/python-net/el/aspose.slides/rectangle) | Το ορθογώνιο προς δοκιμή. Δέχεται οποιοδήποτε αντικείμενο με ιδιότητες `x`, `y`, `width` και `height`. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **TypeError** | Wrong number of arguments. |


## contains(self, x, y) {#int-int}
Καθορίζει εάν το συγκεκριμένο σημείο βρίσκεται μέσα σε αυτό το ορθογώνιο.

### Επιστρέφει

`True` if the point defined by `x` and `y` is contained within this rectangle; otherwise, `False`.



```python
def contains(self, x, y):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **int** | Η συντεταγμένη x του σημείου προς δοκιμή. |
| y | **int** | Η συντεταγμένη y του σημείου προς δοκιμή. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **TypeError** | Wrong number of arguments. |



### Δείτε επίσης
* κλάση [`Point`](/slides/python-net/el/aspose.slides/point)
* κλάση [`Rectangle`](/slides/python-net/el/aspose.slides/rectangle)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)