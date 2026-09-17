---
title: insert_section_zoom_frame method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/ishapecollection/insert_section_zoom_frame/
weight: 300
---
## insert_section_zoom_frame(self, index, x, y, width, height, section) {#int-float-float-float-float-isection}
Δημιουργεί ένα νέο πλαίσιο Section Zoom και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.

### Returns

Το νέο δημιουργημένο [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το πλαίσιο Section Zoom. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου Section Zoom, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου Section Zoom, σε σημεία. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Το [`ISection`](/slides/python-net/el/aspose.slides/isection) που αναφέρεται από το πλαίσιο Section Zoom;<br/><br/>            πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκπεμπόμενο αν η αναφερόμενη ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |


## insert_section_zoom_frame(self, index, x, y, width, height, section, image) {#int-float-float-float-float-isection-ippimage}
Δημιουργεί ένα νέο πλαίσιο Section Zoom με προκαθορισμένη εικόνα και το εισάγει στη συλλογή σχήματος στη συγκεκριμένη θέση.

### Returns

Το νέο δημιουργημένο [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe).



```python
def insert_section_zoom_frame(self, index, x, y, width, height, section, image):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Ο δείκτης μηδενικής βάσης στον οποίο θα εισαχθεί το πλαίσιο Section Zoom. |
| x | **float** | Η συντεταγμένη x του νέου πλαισίου Section Zoom, σε σημεία. |
| y | **float** | Η συντεταγμένη y του νέου πλαισίου Section Zoom, σε σημεία. |
| width | **float** | Το πλάτος του νέου πλαισίου Section Zoom, σε σημεία. |
| height | **float** | Το ύψος του νέου πλαισίου Section Zoom, σε σημεία. |
| section | [`ISection`](/slides/python-net/el/aspose.slides/isection) | Το [`ISection`](/slides/python-net/el/aspose.slides/isection) που αναφέρεται από το πλαίσιο Section Zoom;<br/><br/>            πρέπει να ανήκει σε αυτήν την παρουσίαση και να περιέχει τουλάχιστον μία διαφάνεια. |
| image | [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage) | Η εικόνα που θα εμφανίζεται εντός του πλαισίου Section Zoom. |

### Exceptions

| Exception | Description |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentException))** | Εκπεμπόμενο αν η αναφερόμενη ενότητα δεν ανήκει στην τρέχουσα παρουσίαση ή δεν περιέχει διαφάνειες. |



### See Also
* κλάση [`IPPImage`](/slides/python-net/el/aspose.slides/ippimage)
* κλάση [`ISection`](/slides/python-net/el/aspose.slides/isection)
* κλάση [`ISectionZoomFrame`](/slides/python-net/el/aspose.slides/isectionzoomframe)
* κλάση [`IShapeCollection`](/slides/python-net/el/aspose.slides/ishapecollection)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)