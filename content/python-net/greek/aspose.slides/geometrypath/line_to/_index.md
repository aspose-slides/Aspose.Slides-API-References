---
title: line_to method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/geometrypath/line_to/
weight: 50
---
## line_to(self, point) {#asposepydrawingpointf}
Προσθέτει γραμμή στο τέλος του μονοπατιού


```python
def line_to(self, point):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Τελικό σημείο της γραμμής |


## line_to(self, x, y) {#float-float}
Προσθέτει γραμμή στο τέλος του μονοπατιού


```python
def line_to(self, x, y):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Συντεταγμένη X του τελικού σημείου της γραμμής |
| y | **float** | Συντεταγμένη Y του τελικού σημείου της γραμμής |


## line_to(self, point, index) {#asposepydrawingpointf-int}
Προσθέτει γραμμή στην καθορισμένη θέση του μονοπατιού


```python
def line_to(self, point, index):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| point | **aspose.slides.PointF** | Τελικό σημείο |
| index | **int** | Δείκτης του τμήματος στο PathData |

### Exceptions

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ο δείκτης του τμήματος είναι εκτός του εύρους του PathData |


## line_to(self, x, y, index) {#float-float-int}
Προσθέτει γραμμή στην καθορισμένη θέση του μονοπατιού


```python
def line_to(self, x, y, index):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Συντεταγμένη X του σημείου |
| y | **float** | Συντεταγμένη Y του σημείου |
| index | **int** | Δείκτης του τμήματος στο PathData |

### Exceptions

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentOutOfRangeException))** | Ο δείκτης του τμήματος είναι εκτός του εύρους του PathData |



### See Also
* κλάση [`GeometryPath`](/slides/python-net/el/aspose.slides/geometrypath)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)