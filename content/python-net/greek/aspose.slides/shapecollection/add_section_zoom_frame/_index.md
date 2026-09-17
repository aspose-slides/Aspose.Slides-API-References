---
title: add_section_zoom_frame method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/shapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Δημιουργεί ένα νέο Section Zoom frame και το προσθέτει στο τέλος της συλλογής σχήματος.

### Επιστρέφει

Το νέο δημιουργημένο [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου Section Zoom frame, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου Section Zoom frame, σε σημεία. |
| width | **float** | Το πλάτος του νέου Section Zoom frame, σε σημεία. |
| height | **float** | Το ύψος του νέου Section Zoom frame, σε σημεία. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Το [`ISection`](/slides/python-net/el/aspose.slides/isection) που αναφέρεται από το Section Zoom frame;<br/><br/>πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ενδείκνυται εάν η εν λόγω ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |


## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Δημιουργεί ένα νέο Section Zoom frame με προορισμένο εικόνα και το προσθέτει στο τέλος της συλλογής σχήματος.

### Επιστρέφει

Το νέο δημιουργημένο [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe).



```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η συντεταγμένη x του νέου Section Zoom frame, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου Section Zoom frame, σε σημεία. |
| width | **float** | Το πλάτος του νέου Section Zoom frame, σε σημεία. |
| height | **float** | Το ύψος του νέου Section Zoom frame, σε σημεία. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Το [`ISection`](/slides/python-net/el/aspose.slides/isection) που αναφέρεται από το Section Zoom frame;<br/><br/>πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Το [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) που θα εμφανιστεί εντός του Section Zoom frame. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Ενδείκνυται εάν η εν λόγω ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |



### Δείτε επίσης
* κλάση [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* κλάση [`ISection`](/slides/python-net/el/aspose.slides/isection)
* κλάση [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe)
* κλάση [`ShapeCollection`](/slides/python-net/el/aspose.slides/shapecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)