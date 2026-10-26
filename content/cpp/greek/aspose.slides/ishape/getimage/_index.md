---
title: GetImage()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Επιστρέφει μικρογραφία σχήματος. Το είδος ορίων μικρογραφίας σχήματος ShapeThumbnailBounds::Shape χρησιμοποιείται από προεπιλογή."
type: docs
weight: 547
url: /el/aspose.slides/ishape/getimage/
---
## IShape::GetImage() μέθοδος

Επιστρέφει τη μικρογραφία του σχήματος. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) τύπος ορίων μικρογραφίας σχήματος χρησιμοποιείται από προεπιλογή.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```

### Τιμή Επιστροφής

[Shape](../../shape/) μικρογραφία.

## IShape::GetImage(ShapeThumbnailBounds, float, float) μέθοδος

Επιστρέφει τη μικρογραφία του σχήματος.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) τύπο ορίων μικρογραφίας. |
| scaleX | **float** | Κλίμακα X |
| scaleY | **float** | Κλίμακα Y |

### Τιμή Επιστροφής

[Shape](../../shape/) μικρογραφία ή null σε περίπτωση που [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) χρησιμοποιείται και ένα σχήμα δεν έχει ορατά στοιχεία.

## Δείτε επίσης

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)