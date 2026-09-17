---
title: add_section_zoom_frame method
second_title: Aspose.Slides for Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ishapecollection/add_section_zoom_frame/
weight: 120
---
## add_section_zoom_frame(self, x, y, width, height, section) {#float-float-float-float-isection}
Δημιουργεί ένα νέο Section Zoom frame και το προσθέτει στο τέλος της shape collection.

### Επιστροφή

Το νεοδημιουργημένο [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe).

```python
def add_section_zoom_frame(self, x, y, width, height, section):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η x-συντεταγμένη του νέου Section Zoom frame, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του νέου Section Zoom frame, σε σημεία. |
| width | **float** | Το πλάτος του νέου Section Zoom frame, σε σημεία. |
| height | **float** | Το ύψος του νέου Section Zoom frame, σε σημεία. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Το [`ISection`](/slides/python-net/el/aspose.slides/isection) που αναφέρεται από το Section Zoom frame· <br/><br/>            πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκβάλεται εάν η εν λόγω ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |

## add_section_zoom_frame(self, x, y, width, height, section, image) {#float-float-float-float-isection-ippimage}
Δημιουργεί ένα νέο Section Zoom frame με μια προορισμένη εικόνα και το προσθέτει στο τέλος της shape collection.

### Επιστροφή

Το νεοδημιουργημένο [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe).

```python
def add_section_zoom_frame(self, x, y, width, height, section, image):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| x | **float** | Η x-συντεταγμένη του νέου Section Zoom frame, σε σημεία. |
| y | **float** | Η y-συντεταγμένη του νέου Section Zoom frame, σε σημεία. |
| width | **float** | Το πλάτος του νέου Section Zoom frame, σε σημεία. |
| height | **float** | Το ύψος του νέου Section Zoom frame, σε σημεία. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Το [`ISection`](/slides/python-net/el/aspose.slides/isection) που αναφέρεται από το Section Zoom frame· <br/><br/>            πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Το [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) που θα εμφανιστεί εντός του Section Zoom frame. |

### Εξαιρέσεις

| Εξαίρεση | Περιγραφή |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκβάλεται εάν η εν λόγω ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |

### Δείτε επίσης
* class [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* class [`ISection`](/slides/python-net/el/aspose.slides/isection)
* class [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe)
* class [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* module [`aspose.slides`](/slides/python-net/el/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)