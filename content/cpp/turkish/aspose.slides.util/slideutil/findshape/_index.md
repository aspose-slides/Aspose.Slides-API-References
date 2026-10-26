---
title: FindShape()
second_title: Aspose.Slides for C++ API Referansı
description: PPTX sunumunda alternatif metne göre şekil bul.
type: docs
weight: 1
url: /tr/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) method


PPTX sunumunda alternatif metne göre şekil bulur.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Taranan sunum. |
| altText | [System::String](../../../system/string/) | Bir şeklin alternatif metni. |

### Dönüş Değeri

[Shape](../../../aspose.slides/shape/) veya null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) method


PPTX sunumunda bir slaytta alternatif metne göre şekil bulur.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Taranan slayt. |
| altText | [System::String](../../../system/string/) | Bir şeklin alternatif metni. |

### Dönüş Değeri

[Shape](../../../aspose.slides/shape/) veya null.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)