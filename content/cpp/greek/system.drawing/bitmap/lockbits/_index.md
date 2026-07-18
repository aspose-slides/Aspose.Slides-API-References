---
title: LockBits()
second_title: Aspose.Slides για την αναφορά API του C++
description: Κλειδώνει ένα Bitmap στη μνήμη του συστήματος.
type: docs
weight: 118
url: /el/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) μέθοδος

Κλειδώνει ένα [Bitmap](../) στη μνήμη του συστήματος.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Ένα ορθογώνιο που καθορίζει την περιοχή της εικόνας που θα κλειδ ωθεί |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Καθορίζει το επίπεδο πρόσβασης στο bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Η μορφή δεδομένων αυτού του bitmap |

### Τιμή Επιστροφής

Ένας κοινόχρηστος δείκτης σε ένα αντικείμενο BitmapData που περιέχει πληροφορίες σχετικά με την εκτελεσμένη λειτουργία κλειδώματος

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) μέθοδος

Κλειδώνει ένα [Bitmap](../) στη μνήμη του συστήματος.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Ένα ορθογώνιο που καθορίζει την περιοχή της εικόνας που θα κλειδ ωθεί |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Καθορίζει το επίπεδο πρόσβασης στο bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Η μορφή δεδομένων αυτού του bitmap |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Περιέχει πληροφορίες σχετικά με τη λειτουργία κλειδώματος |

### Τιμή Επιστροφής

Ένας κοινόχρηστος δείκτης σε ένα αντικείμενο BitmapData που περιέχει πληροφορίες σχετικά με την εκτελεσμένη λειτουργία κλειδώματος

## Δείτε επίσης

* Απαρίθμηση [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Απαρίθμηση [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Ορισμός Τύπου [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Κλάση [Rectangle](../../rectangle/)
* Κλάση [Bitmap](../)
* Χώρος Ονομάτων [System::Drawing](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)