---
title: FindShape()
second_title: Aspose.Slides für C++ API-Referenz
description: Finde Shape nach Alternativtext in einer PPTX-Präsentation.
type: docs
weight: 1
url: /de/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) Methode


Finde shape nach Alternativtext in einer PPTX-Präsentation.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Scanned presentation. |
| altText | [System::String](../../../system/string/) | Alternative text of a shape. |

### Rückgabewert

[Shape](../../../aspose.slides/shape/) oder null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) Methode


Finde shape nach Alternativtext auf einer Folie in einer PPTX-Präsentation.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Scanned slide. |
| altText | [System::String](../../../system/string/) | Alternative text of a shape. |

### Rückgabewert

[Shape](../../../aspose.slides/shape/) oder null.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../../aspose.slides/ishape/)
* Klasse [IPresentation](../../../aspose.slides/ipresentation/)
* Klasse [String](../../../system/string/)
* Klasse [SlideUtil](../)
* Klasse [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Namensraum [Aspose::Slides::Util](../../)
* Bibliothek [Aspose.Slides](../../../)