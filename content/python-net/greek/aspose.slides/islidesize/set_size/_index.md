---
title: set_size method
second_title: Aspose.Slides για Python μέσω .NET API Αναφορά
description: 
type: docs
url: /el/aspose.slides/islidesize/set_size/
weight: 10
---
## set_size(self, type, scale_type) {#slidesizetype-slidesizescaletype}
Ορίζει το μέγεθος της διαφάνειας ανά τύπο και κλιμακώνει το υπάρχον περιεχόμενο.


```python
def set_size(self, type, scale_type):
    ...
```


| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| type | [`SlideSizeType`](/slides/python-net/el/aspose.slides/slidesizetype) | Ο προ-ορισμένος τύπος διαφάνειας που θα εφαρμοστεί. |
| scale_type | [`SlideSizeScaleType`](/slides/python-net/el/aspose.slides/slidesizescaletype) | Η λειτουργία κλιμάκωσης του περιεχομένου που θα χρησιμοποιηθεί. |

### Σχόλια

Η ανάθεση οποιασδήποτε τιμής εκτός του [`SlideSizeType.CUSTOM`](/slides/python-net/el/aspose.slides/slidesizetype/CUSTOM) προσαρμόζει το [`ISlideSize.size`](/slides/python-net/el/aspose.slides/islidesize/size) βάσει του επιλεγμένου τύπου, διατηρώντας το [`ISlideSize.orientation`](/slides/python-net/el/aspose.slides/islidesize/orientation).


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

### Σχόλια

Αυτό επαναφέρει την ιδιότητα [`ISlideSize.type`](/slides/python-net/el/aspose.slides/islidesize/type) στο [`SlideSizeType.CUSTOM`](/slides/python-net/el/aspose.slides/slidesizetype/CUSTOM) και ορίζει το [`ISlideSize.orientation`](/slides/python-net/el/aspose.slides/islidesize/orientation).



### Δείτε επίσης
* κλάση [`ISlideSize`](/slides/python-net/el/aspose.slides/islidesize)
* απαρίθμηση [`SlideSizeScaleType`](/slides/python-net/el/aspose.slides/slidesizescaletype)
* απαρίθμηση [`SlideSizeType`](/slides/python-net/el/aspose.slides/slidesizetype)
* μονάδα [`aspose.slides`](/slides/python-net/el/aspose.slides)
* βιβλιοθήκη [`Aspose.Slides`](/slides/python-net)