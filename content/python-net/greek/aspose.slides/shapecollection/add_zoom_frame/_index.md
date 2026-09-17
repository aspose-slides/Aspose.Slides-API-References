---
title: add_zoom_frame method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/shapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

### Επιστρέφει

Το νεοδημιουργημένο [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε μονάδες (points). |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε μονάδες (points). |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε μονάδες (points). |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε μονάδες (points). |
| slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Το [`ISlide`](/slides/python-net/el/aspose.slides/islide) που αναφέρεται από το πλαίσιο Zoom;<br/><br/> πρέπει να ανήκει σε αυτήν την παρουσίαση. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκτοπίζεται εάν το αναφερόμενο slide δεν ανήκει στην τρέχουσα παρουσίαση. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Δημιουργεί ένα νέο πλαίσιο Zoom και το προσθέτει στο τέλος της συλλογής σχημάτων.

### Επιστρέφει

Το νεοδημιουργημένο [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Zoom, σε μονάδες (points). |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Zoom, σε μονάδες (points). |
| width | **float** | Το πλάτος του νέου πλαισίου Zoom, σε μονάδες (points). |
| height | **float** | Το ύψος του νέου πλαισίου Zoom, σε μονάδες (points). |
| slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Το [`ISlide`](/slides/python-net/el/aspose.slides/islide) που αναφέρεται από το πλαίσιο Zoom;<br/><br/> πρέπει να ανήκει σε αυτήν την παρουσίαση. |
| image | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Η εικόνα για το αναφερόμενο slide [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage). |

### Εξαίρεσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκτοπίζεται εάν το αναφερόμενο slide δεν ανήκει στην τρέχουσα παρουσίαση. |



### Δείτε επίσης
* κλάση [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* κλάση [`ISlide`](/slides/python-net/el/aspose.slides/islide)
* κλάση [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe)
* κλάση [`ShapeCollection`](/slides/python-net/el/aspose.slides/shapecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)