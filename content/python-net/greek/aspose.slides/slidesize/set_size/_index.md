---
title: set_size method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/slidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Ορίζει το μέγεθος της διαφάνειας με βάση τον τύπο και κλιμακώνει το υπάρχον περιεχόμενο.

```python
def set_size(self, type, scale_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/el/aspose.slides/slidesizetype) | Ο προκαθορισμένος τύπος διαφάνειας που θα εφαρμοστεί. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/el/aspose.slides/slidesizescaletype) | Η λειτουργία κλιμάκωσης του περιεχομένου που θα χρησιμοποιηθεί. |

### Παρατηρήσεις

Αναθέτοντας οποιαδήποτε τιμή εκτός του [`SlideSizeType.CUSTOM`](/slides/python-net/el/aspose.slides/slidesizetype/CUSTOM) ρυθμίζει το [`SlideSize.size`](/slides/python-net/el/aspose.slides/slidesize/size) βάσει του επιλεγμένου τύπου, διατηρώντας το [`SlideSize.orientation`](/slides/python-net/el/aspose.slides/slidesize/orientation).

## set_size(self, width, height, scale_type) {#float-float-slidesizescaletype}
Ορίζει ρητά τις διαστάσεις της διαφάνειας και κλιμακώνει το υπάρχον περιεχόμενο.

```python
def set_size(self, width, height, scale_type):
    ...
```

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| width | **float** | Το νέο πλάτος της διαφάνειας, σε σημεία. |
| height | **float** | Το νέο ύψος της διαφάνειας, σε σημεία. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/el/aspose.slides/slidesizescaletype) | Η λειτουργία κλιμάκωσης του περιεχομένου που θα χρησιμοποιηθεί. |

### Παρατηρήσεις

Αυτό επαναρυθμίζει την ιδιότητα [`SlideSize.type`](/slides/python-net/el/aspose.slides/slidesize/type) σε [`SlideSizeType.CUSTOM`](/slides/python-net/el/aspose.slides/slidesizetype/CUSTOM) και ορίζει το [`SlideSize.orientation`](/slides/python-net/el/aspose.slides/slidesize/orientation).

### Δείτε επίσης
* κλάση [`SlideSize`](/slides/python-net/el/aspose.slides/slidesize)
* απαρίθμηση [`SlideSizeScaleType`](/slides/python-net/el/aspose.slides/slidesizescaletype)
* απαρίθμηση [`SlideSizeType`](/slides/python-net/el/aspose.slides/slidesizetype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)