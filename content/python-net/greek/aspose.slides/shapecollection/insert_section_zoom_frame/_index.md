---
title: insert_section_zoom_frame method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/shapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Δημιουργεί ένα νέο Section Zoom frame και το εισάγει στη shape collection στη θέση που καθορίζεται από τον δείκτη.

### Returns

Το νέο δημιουργημένο [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης στο οποίο θα εισαχθεί το Section Zoom frame. |
| x | **float** | Η x-συντεταγμένη του νέου Section Zoom frame, σε points. |
| y | **float** | Η y-συντεταγμένη του νέου Section Zoom frame, σε points. |
| width | **float** | Το πλάτος του νέου Section Zoom frame, σε points. |
| height | **float** | Το ύψος του νέου Section Zoom frame, σε points. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Το [`ISection`](/slides/python-net/el/aspose.slides/isection) που αναφέρεται από το Section Zoom frame· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μια διαφάνεια. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκδίδεται εάν η αναφερόμενη ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Δημιουργεί ένα νέο Section Zoom frame με προορισμένη εικόνα και το εισάγει στη shape collection στη θέση που καθορίζεται από τον δείκτη.

### Returns

Το νέο δημιουργημένο [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης στο οποίο θα εισαχθεί το Section Zoom frame. |
| x | **float** | Η x-συντεταγμένη του νέου Section Zoom frame, σε points. |
| y | **float** | Η y-συντεταγμένη του νέου Section Zoom frame, σε points. |
| width | **float** | Το πλάτος του νέου Section Zoom frame, σε points. |
| height | **float** | Το ύψος του νέου Section Zoom frame, σε points. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Το [`ISection`](/slides/python-net/el/aspose.slides/isection) που αναφέρεται από το Section Zoom frame· πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μια διαφάνεια. |
| image | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Η εικόνα που θα εμφανιστεί μέσα στο Section Zoom frame. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκδίδεται εάν η αναφερόμενη ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |



### See Also
* κλάση [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* κλάση [`ISection`](/slides/python-net/el/aspose.slides/isection)
* κλάση [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe)
* κλάση [`ShapeCollection`](/slides/python-net/el/aspose.slides/shapecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)