---
title: FindShape()
second_title: Aspose.Slides för C++ API-referens
description: Hitta figur efter alternativ text i en PPTX-presentation.
type: docs
weight: 1
url: /sv/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) metod

Hitta figur efter alternativ text i en PPTX-presentation.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Skannad presentation. |
| altText | [System::String](../../../system/string/) | Alternativ text för en figur. |

### Returvärde

[Shape](../../../aspose.slides/shape/) eller null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) metod

Hitta figur efter alternativ text på en bild i en PPTX-presentation.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Skannad bild. |
| altText | [System::String](../../../system/string/) | Alternativ text för en figur. |

### Returvärde

[Shape](../../../aspose.slides/shape/) eller null.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IShape](../../../aspose.slides/ishape/)
* Klass [IPresentation](../../../aspose.slides/ipresentation/)
* Klass [String](../../../system/string/)
* Klass [SlideUtil](../)
* Klass [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Namnrymd [Aspose::Slides::Util](../../)
* Bibliotek [Aspose.Slides](../../../)