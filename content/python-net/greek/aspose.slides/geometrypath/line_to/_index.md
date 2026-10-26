---
title: line_to method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposeslidespointf}
Προσθέτει γραμμή στο τέλος της διαδρομής


```python
def line_to(self, point):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/el/aspose.slides/pointf) | Τελικό σημείο της γραμμής |


## line_to(self, x, y) {#float-float}
Προσθέτει γραμμή στο τέλος της διαδρομής


```python
def line_to(self, x, y):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Συντεταγμένη X του τελικού σημείου της γραμμής |
| y | **float** | Συντεταγμένη Y του τελικού σημείου της γραμμής |


## line_to(self, point, index) {#asposeslidespointf-int}
Προσθέτει γραμμή στο σημείο που καθορίζεται στη διαδρομή


```python
def line_to(self, point, index):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | [`PointF`](/slides/python-net/el/aspose.slides/pointf) | Τελικό σημείο |
| index | **int** | Δείκτης του τμήματος στο PathData |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ο δείκτης του τμήματος είναι εκτός του εύρους του PathData |


## line_to(self, x, y, index) {#float-float-int}
Προσθέτει γραμμή στο σημείο που καθορίζεται στη διαδρομή


```python
def line_to(self, x, y, index):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Συντεταγμένη X του σημείου |
| y | **float** | Συντεταγμένη Y του σημείου |
| index | **int** | Δείκτης του τμήματος στο PathData |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ο δείκτης του τμήματος είναι εκτός του εύρους του PathData |



### Δείτε επίσης
* κλάση [`GeometryPath`](/slides/python-net/el/aspose.slides/geometrypath)
* κλάση [`PointF`](/slides/python-net/el/aspose.slides/pointf)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)