---
title: GetTile()
second_title: Aspose.Slides για την αναφορά API C++
description: Δημιουργεί μια εικόνα πλακιδίου για το γέμισμα μοτίβου με καθορισμένα χρώματα.
type: docs
weight: 53
url: /el/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) μέθοδος

Δημιουργεί μια εικόνα πλακιδίου για γέμισμα μοτίβου με συγκεκριμένα χρώματα.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Το φόντο [System::Drawing::Color](../../../system.drawing/color/) για το μοτίβο. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Το προσκήνιο [System::Drawing::Color](../../../system.drawing/color/) για το μοτίβο. |

### Τιμή επιστροφής

Πλακίδιο [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) μέθοδος

Δημιουργεί μια εικόνα πλακιδίου για γέμισμα μοτίβου.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Η προεπιλεγμένη [System::Drawing::Color](../../../system.drawing/color/), ορισμένη στο αντικείμενο StyleEx του ShapeEx. Τα χρώματα του γεμίσματος μπορεί να εξαρτώνται από αυτό. |

### Τιμή επιστροφής

Πλακίδιο [IImage](../../iimage/).

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IImage](../../iimage/)
* Κλάση [Color](../../../system.drawing/color/)
* Κλάση [IPatternFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)