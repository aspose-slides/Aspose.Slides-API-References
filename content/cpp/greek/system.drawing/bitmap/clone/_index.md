---
title: Clone()
second_title: Aspose.Slides για C++ API Reference
description: Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου.
type: docs
weight: 183
url: /el/system.drawing/bitmap/clone/
---
## Bitmap::Clone() μέθοδος

Δημιουργεί ένα αντίγραφο του τρέχοντος αντικειμένου.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```

### Τιμή επιστροφής

Ένα αντίγραφο του τρέχοντος αντικειμένου.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) μέθοδος

Δημιουργεί ένα [Bitmap](../) αντικείμενο που αντιπροσωπεύει ένα αντίγραφο μιας περιοχής της bitmap εικόνας που αναπαριστάται από το τρέχον αντικείμενο.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Το ορθογώνιο που καθορίζει την περιοχή προς αντιγραφή |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Η μορφή εικονοστοιχείων για το νέο [Bitmap](../) |

### Τιμή επιστροφής

Το δημιουργημένο [Bitmap](../) αντικείμενο

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) μέθοδος

Δημιουργεί ένα [Bitmap](../) αντικείμενο που αντιπροσωπεύει ένα αντίγραφο μιας περιοχής της bitmap εικόνας που αναπαριστάται από το τρέχον αντικείμενο.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Το ορθογώνιο που καθορίζει την περιοχή προς αντιγραφή |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Η μορφή εικονοστοιχείων για το νέο [Bitmap](../) |

### Τιμή επιστροφής

Το δημιουργημένο [Bitmap](../) αντικείμενο

## Δείτε επίσης

* Απαρίθμηση [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [Image](../../image/)
* Κλάση [Bitmap](../)
* Κλάση [Rectangle](../../rectangle/)
* Κλάση [RectangleF](../../rectanglef/)
* Χώρος ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)