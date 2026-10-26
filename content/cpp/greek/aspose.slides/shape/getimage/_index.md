---
title: GetImage()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Επιστρέφει τη μικρογραφία του σχήματος. Ο τύπος ορίων μικρογραφίας ShapeThumbnailBounds::Shape χρησιμοποιείται εξ ορισμού."
type: docs
weight: 651
url: /el/aspose.slides/shape/getimage/
---
## Shape::GetImage() μέθοδος

Επιστρέφει τη μικρογραφία του σχήματος. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) τύπος ορίων μικρογραφίας σχήματος χρησιμοποιείται εξ ορισμού.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### Τιμή Επιστροφής

[Shape](../) μικρογραφία.

## Shape::GetImage(ShapeThumbnailBounds, float, float) μέθοδος

Επιστρέφει τη μικρογραφία του σχήματος.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) τύπος ορίων μικρογραφίας. |
| scaleX | **float** | Κλίμακα X |
| scaleY | **float** | Κλίμακα Y |

### Τιμή Επιστροφής

[Shape](../) μικρογραφία ή null στην περίπτωση που [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) χρησιμοποιείται και ένα σχήμα δεν έχει ορατά στοιχεία.

## Δείτε επίσης

* Απαρίθμηση [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IImage](../../iimage/)
* Κλάση [Shape](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)