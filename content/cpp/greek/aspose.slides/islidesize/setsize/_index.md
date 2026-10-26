---
title: SetSize()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ορίζει το μέγεθος της διαφάνειας με βάση τον τύπο και κλιμακώνει το υπάρχον περιεχόμενο. Η ανάθεση οποιασδήποτε τιμής εκτός του SlideSizeType::Custom προσαρμόζει το ISlideSize::get_Size βάσει του επιλεγμένου τύπου, διατηρώντας το ISlideSize::get_Orientation."
type: docs
weight: 53
url: /el/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) μέθοδος

Ορίζει το μέγεθος της διαφάνειας με βάση τον τύπο και κλιμακώνει το υπάρχον περιεχόμενο. Η ανάθεση οποιασδήποτε τιμής εκτός του [SlideSizeType::Custom](../../slidesizetype/) προσαρμόζει το [ISlideSize::get_Size](../get_size/) βάσει του επιλεγμένου τύπου, διατηρώντας το [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Το προκαθορισμένο μέγεθος διαφάνειας που θα εφαρμοστεί. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Η λειτουργία κλιμάκωσης περιεχομένου που θα χρησιμοποιηθεί. |
## Σχόλια

Η ανάθεση οποιασδήποτε τιμής εκτός του [SlideSizeType::Custom](../../slidesizetype/) προσαρμόζει το [System::Drawing::Size](../../../system.drawing/size/) βάσει του επιλεγμένου τύπου, διατηρώντας το [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) μέθοδος

Ορίζει ρητά τις διαστάσεις της διαφάνειας και κλιμακώνει το υπάρχον περιεχόμενο. Αυτό επαναφέρει την τιμή [ISlideSize::get_Type](../get_type/) στο [SlideSizeType::Custom](../../slidesizetype/) και ορίζει το [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| width | **float** | Το νέο πλάτος της διαφάνειας, σε σημείο. |
| height | **float** | Το νέο ύψος της διαφάνειας, σε σημείο. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Η λειτουργία κλιμάκωσης περιεχομένου που θα χρησιμοποιηθεί. |
## Σχόλια

Αυτό επαναφέρει την ιδιότητα [ISlideSize::get_Type](../get_type/) σε [SlideSizeType::Custom](../../slidesizetype/) και ορίζει το [Orientation](../../orientation/). 

## Δείτε επίσης

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Κλάση [ISlideSize](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)