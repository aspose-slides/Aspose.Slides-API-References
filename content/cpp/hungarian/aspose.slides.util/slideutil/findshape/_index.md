---
title: FindShape()
second_title: Aspose.Slides C++ API hivatkozás
description: Alakzat keresése alternatív szöveg alapján egy PPTX prezentációban.
type: docs
weight: 1
url: /hu/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) metódus

Alakzat keresése alternatív szöveg alapján egy PPTX prezentációban.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Beolvasott prezentáció. |
| altText | [System::String](../../../system/string/) | Alakzat alternatív szövege. |

### Visszatérési érték

[Shape](../../../aspose.slides/shape/) vagy null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) metódus

Alakzat keresése alternatív szöveg alapján egy dián egy PPTX prezentációban.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Beolvasott dia. |
| altText | [System::String](../../../system/string/) | Alakzat alternatív szövege. |

### Visszatérési érték

[Shape](../../../aspose.slides/shape/) vagy null.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)