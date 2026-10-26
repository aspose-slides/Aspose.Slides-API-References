---
title: FindShape()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Najde tvar podle alternativního textu v prezentaci PPTX.
type: docs
weight: 1
url: /cs/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) metoda

Najde tvar podle alternativního textu v prezentaci PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Skenovaná prezentace. |
| altText | [System::String](../../../system/string/) | Alternativní text tvaru. |

### Návratová hodnota

[Shape](../../../aspose.slides/shape/) nebo null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) metoda

Najde tvar podle alternativního textu na snímku v prezentaci PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Skenovaný snímek. |
| altText | [System::String](../../../system/string/) | Alternativní text tvaru. |

### Návratová hodnota

[Shape](../../../aspose.slides/shape/) nebo null.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IShape](../../../aspose.slides/ishape/)
* Třída [IPresentation](../../../aspose.slides/ipresentation/)
* Třída [String](../../../system/string/)
* Třída [SlideUtil](../)
* Třída [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Jmenný prostor [Aspose::Slides::Util](../../)
* Knihovna [Aspose.Slides](../../../)