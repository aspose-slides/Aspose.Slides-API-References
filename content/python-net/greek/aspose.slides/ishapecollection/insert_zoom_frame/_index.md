---
title: insert_zoom_frame method
second_title: Aspose.Slides για Python μέσω .NET API Reference
description: 
type: docs
url: /el/aspose.slides/ishapecollection/insert_zoom_frame/
weight: 340
---
## insert_zoom_frame(self, index, x, y, width, height, slide) {#int-float-float-float-float-islide}
Δημιουργεί ένα νέο πλαίσιο Zoom και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

### Επιστρέφει

Το νέο δημιουργημένο [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το πλαίσιο Zoom. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε μονάδες point. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε μονάδες point. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε μονάδες point. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε μονάδες point. |
| slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Το [`ISlide`](/slides/python-net/el/aspose.slides/islide) που παραπέμπεται από το πλαίσιο Zoom. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκτελείται εάν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |


## insert_zoom_frame(self, index, x, y, width, height, slide, image) {#int-float-float-float-float-islide-ippimage}
Δημιουργεί ένα νέο πλαίσιο Zoom με προρυθμένη εικόνα και το εισάγει στη συλλογή σχημάτων στον καθορισμένο δείκτη.

### Επιστρέφει

Το νέο δημιουργημένο [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe).



```python
def insert_zoom_frame(self, index, x, y, width, height, slide, image):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| index | **int** | Ο μηδενικός δείκτης στον οποίο θα εισαχθεί το πλαίσιο Zoom. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε μονάδες point. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε μονάδες point. |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε μονάδες point. |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε μονάδες point. |
| slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Το [`ISlide`](/slides/python-net/el/aspose.slides/islide) που παραπέμπεται από το πλαίσιο Zoom. |
| image | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Η εικόνα για τη διαφάνεια [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) που παραπέμπεται. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκτελείται εάν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |



### Δείτε επίσης
* κλάση [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* κλάση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* κλάση [`ISlide`](/slides/python-net/el/aspose.slides/islide)
* κλάση [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)