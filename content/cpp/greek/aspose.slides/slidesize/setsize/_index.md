---
title: SetSize()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει το μέγεθος της διαφάνειας βάσει τύπου και κλιμακώνει το υπάρχον περιεχόμενο.
type: docs
weight: 53
url: /el/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) μέθοδος

Ορίζει το μέγεθος της διαφάνειας βάσει τύπου και κλιμακώνει το υπάρχον περιεχόμενο.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Το προκαθορισμένο μέγεθος διαφάνειας που θα εφαρμοστεί. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Η λειτουργία κλιμάκωσης του περιεχομένου που θα χρησιμοποιηθεί. |

## Παρατηρήσεις

Η ανάθεση οποιασδήποτε τιμής διαφορετικής από [SlideSizeType::Custom](../../slidesizetype/) προσαρμόζει το [SlideSize::get_Size](../get_size/) βάσει του επιλεγμένου τύπου, διατηρώντας ταυτόχρονα το [SlideSize::get_Orientation](../get_orientation/).

## SlideSize::SetSize(float, float, SlideSizeScaleType) μέθοδος

Ορίζει τις διαστάσεις της διαφάνειας ρητά και κλιμακώνει το υπάρχον περιεχόμενο.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | **float** | Το νέο πλάτος της διαφάνειας, σε μονάδες σημείων. |
| height | **float** | Το νέο ύψος της διαφάνειας, σε μονάδες σημείων. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Η λειτουργία κλιμάκωσης του περιεχομένου που θα χρησιμοποιηθεί. |

## Παρατηρήσεις

Αυτό επαναφέρει την ιδιότητα [SlideSize::get_Type](../get_type/) στο [SlideSizeType::Custom](../../slidesizetype/) και ορίζει το [Orientation](../../orientation/).

## Δείτε επίσης

* Απαρίθμηση [SlideSizeType](../../slidesizetype/)
* Απαρίθμηση [SlideSizeScaleType](../../slidesizescaletype/)
* Κλάση [SlideSize](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)