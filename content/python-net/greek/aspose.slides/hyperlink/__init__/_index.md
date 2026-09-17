---
title: Hyperlink constructor
second_title: Aspose.Slides για Python μέσω .NET Αναφορά API
description: 
type: docs
url: /el/aspose.slides/hyperlink/__init__/
weight: 10
---
## __init__(self, url) {#str}
Δημιουργεί μια παρουσία υπερσυνδέσμου.


```python
def __init__(self, url):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| url | **str** | Hyperlink URL. |


## __init__(self, slide) {#islide}
Δημιουργεί μια παρουσία υπερσυνδέσμου που δείχνει σε συγκεκριμένη διαφάνεια.
            Σημείωση: created hyperlink should be assigned to some object from the same presentation, otherwise link will be saved as NoAction.


```python
def __init__(self, slide):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| slide | [`ISlide`](/slides/python-net/el/aspose.slides/islide) | Target slide. |


## __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click) {#hyperlink-str-str-bool-bool-bool}
Δημιουργεί μια παρουσία υπερσυνδέσμου χρησιμοποιώντας έναν άλλο υπερσύνδεσμο ως πηγή, αντικαθιστώντας τις δευτερεύουσες ιδιότητες.


```python
def __init__(self, source, target_frame, tooltip, history, stop_sounds_on_click, highlight_click):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| source | [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink) | Source hyperlink |
| target_frame | **str** | Target frame |
| tooltip | **str** | Tooltip text |
| history | **bool** |  |
| stop_sounds_on_click | **bool** |  |
| highlight_click | **bool** |  |


### Δείτε επίσης
* κλάση [`Hyperlink`](/slides/python-net/el/aspose.slides/hyperlink)
* κλάση [`ISlide`](/slides/python-net/el/aspose.slides/islide)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)