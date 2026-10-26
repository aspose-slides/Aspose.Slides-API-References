---
title: contains method
second_title: Αναφορά API Aspose.Slides για Python μέσω .NET
description: 
type: docs
url: /el/aspose.slides/rectanglef/contains/
weight: 20
---
## contains(self, point) {#pointf}
Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτό το ορθογώνιο.

### Επιστρέφει

`True` εάν το σημείο περιέχεται μέσα σε αυτό το ορθογώνιο· διαφορετικά, `False`.



```python
def contains(self, point):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/el/aspose.slides/pointf) | Το σημείο προς δοκιμή. Δεκτά είναι όσα αντικείμενα έχουν ιδιότητες `x` και `y`. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **TypeError** | Λανθασμένος αριθμός παραμέτρων. |


## contains(self, rect) {#rectanglef}
Καθορίζει εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από το `rect` περιέχεται πλήρως μέσα σε αυτό το ορθογώνιο.

### Επιστρέφει

`True` εάν η ορθογώνια περιοχή που αντιπροσωπεύεται από το `rect` περιέχεται πλήρως μέσα σε αυτό το ορθογώνιο· διαφορετικά, `False`.



```python
def contains(self, rect):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef) | Το ορθογώνιο προς δοκιμή. Δεκτά είναι όσα αντικείμενα έχουν ιδιότητες `x`, `y`, `width` και `height`. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **TypeError** | Λανθασμένος αριθμός παραμέτρων. |


## contains(self, x, y) {#float-float}
Καθορίζει εάν το συγκεκριμένο σημείο περιέχεται μέσα σε αυτό το ορθογώνιο.

### Επιστρέφει

`True` εάν το σημείο που ορίζεται από τα `x` και `y` περιέχεται μέσα σε αυτό το ορθογώνιο· διαφορετικά, `False`.



```python
def contains(self, x, y):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του σημείου προς δοκιμή. |
| y | **float** | Η συντεταγμένη y του σημείου προς δοκιμή. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **TypeError** | Λανθασμένος αριθμός παραμέτρων. |



### Δείτε επίσης
* κλάση [`PointF`](/slides/python-net/el/aspose.slides/pointf)
* κλάση [`RectangleF`](/slides/python-net/el/aspose.slides/rectanglef)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)