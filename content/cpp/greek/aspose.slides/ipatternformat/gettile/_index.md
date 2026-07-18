---
title: GetTile()
second_title: Aspose.Slides για C++ API Αναφορά
description: Δημιουργεί μια εικόνα πλακιδίου για το γεμιστικό μοτίβο με καθορισμένα χρώματα.
type: docs
weight: 53
url: /el/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) μέθοδος

Δημιουργεί μια εικόνα πλακιδίου για το γεμιστικό μοτίβο με καθορισμένα χρώματα.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Το φόντο [System::Drawing::Color](../../../system.drawing/color/) για το μοτίβο. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Το προσκήνιο [System::Drawing::Color](../../../system.drawing/color/) για το μοτίβο. |

### Τιμή Επιστροφής

Πλακίδιο [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) μέθοδος

Δημιουργεί μια εικόνα πλακιδίου για το γεμιστικό μοτίβο.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Η προεπιλεγμένη [System::Drawing::Color](../../../system.drawing/color/), ορισμένη στο αντικείμενο StyleEx του ShapeEx. Τα χρώματα του γεμίσματος μπορεί να εξαρτώνται από αυτήν. |

### Τιμή Επιστροφής

Πλακίδιο [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IImage](../../iimage/)
* Κλάση [Color](../../../system.drawing/color/)
* Κλάση [IPatternFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)