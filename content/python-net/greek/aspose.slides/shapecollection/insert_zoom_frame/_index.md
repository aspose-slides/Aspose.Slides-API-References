---
title: insert_zoom_frame method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/shapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

### Επιστρέφει

Το πρόσφατα δημιουργημένο [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης όπου θα εισαχθεί το πλαίσιο Zoom. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε points. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε points. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε points. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε points. |
| slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Το [`ISlide`](/slides/python-net/el/aspose.slides/islide) που αναφέρεται από το πλαίσιο Zoom. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Παρουσιάζεται εάν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Δημιουργεί ένα νέο πλαίσιο Zoom με προεπιλεγμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

### Επιστρέφει

Το πρόσφατα δημιουργημένο [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης όπου θα εισαχθεί το πλαίσιο Zoom. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε points. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε points. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε points. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε points. |
| slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Το [`ISlide`](/slides/python-net/el/aspose.slides/islide) που αναφέρεται από το πλαίσιο Zoom. |
| image | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Η εικόνα για τη διαφάνεια [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) που αναφέρεται. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Παρουσιάζεται εάν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |



### Δείτε επίσης
* κλάση [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* κλάση [`ISlide`](/slides/python-net/el/aspose.slides/islide)
* κλάση [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe)
* κλάση [`ShapeCollection`](/slides/python-net/el/aspose.slides/shapecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)