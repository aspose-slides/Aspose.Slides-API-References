---
title: add_zoom_frame method
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/ishapecollection/add_zoom_frame/
weight: 170
---
## add_zoom_frame(self, x, y, width, height, slide) {#float-float-float-float-islide}
Δημιουργεί ένα νέο Zoom πλαίσιο και το προσθέτει στο τέλος της συλλογής σχημάτων.

### Returns

Το νεοδημιουργημένο [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου Zoom πλαισίου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου Zoom πλαισίου, σε σημεία. |
| width | **float** | Το πλάτος του νέου Zoom πλαισίου, σε σημεία. |
| height | **float** | Το ύψος του νέου Zoom πλαισίου, σε σημεία. |
| slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Το [`ISlide`](/slides/python-net/el/aspose.slides/islide) που αναφέρεται από το Zoom πλαίσιο· πρέπει να ανήκει σε αυτήν την παρουσίαση. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εμφανίζεται εάν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |


## add_zoom_frame(self, x, y, width, height, slide, image) {#float-float-float-float-islide-ippimage}
Δημιουργεί ένα νέο Zoom πλαίσιο και το προσθέτει στο τέλος της συλλογής σχημάτων.

### Returns

Το νεοδημιουργημένο [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe).



```python
def add_zoom_frame(self, x, y, width, height, slide, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου Zoom πλαισίου, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου Zoom πλαισίου, σε σημεία. |
| width | **float** | Το πλάτος του νέου Zoom πλαισίου, σε σημεία. |
| height | **float** | Το ύψος του νέου Zoom πλαισίου, σε σημεία. |
| slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Το [`ISlide`](/slides/python-net/el/aspose.slides/islide) που αναφέρεται από το Zoom πλαίσιο· πρέπει να ανήκει σε αυτήν την παρουσίαση. |
| image | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Η εικόνα για τη σχετική διαφάνεια [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage). |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εμφανίζεται εάν η αναφερόμενη διαφάνεια δεν ανήκει στην τρέχουσα παρουσίαση. |



### See Also
* class [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* class [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* class [`ISlide`](/slides/python-net/el/aspose.slides/islide)
* class [`IZoomFrame`](/slides/python-net/el/aspose.slides/izoomframe)
* module [`aspose.slides`](/slides/python-net/el/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)