---
title: FindShape()
second_title: Aspose.Slides για C++ Αναφορά API
description: Βρείτε το σχήμα με εναλλακτικό κείμενο σε παρουσίαση PPTX.
type: docs
weight: 1
url: /el/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) μέθοδος

Βρείτε το σχήμα με εναλλακτικό κείμενο σε παρουσίαση PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Σαρωμένη παρουσίαση. |
| altText | [System::String](../../../system/string/) | Εναλλακτικό κείμενο ενός σχήματος. |

### Τιμή Επιστροφής

[Shape](../../../aspose.slides/shape/) ή null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) μέθοδος

Βρείτε το σχήμα με εναλλακτικό κείμενο σε μια διαφάνεια παρουσίασης PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Σαρωμένη διαφάνεια. |
| altText | [System::String](../../../system/string/) | Εναλλακτικό κείμενο ενός σχήματος. |

### Τιμή Επιστροφής

[Shape](../../../aspose.slides/shape/) ή null.

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IShape](../../../aspose.slides/ishape/)
* Κλάση [IPresentation](../../../aspose.slides/ipresentation/)
* Κλάση [String](../../../system/string/)
* Κλάση [SlideUtil](../)
* Κλάση [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Χώρος ονομάτων [Aspose::Slides::Util](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)