---
title: FindShape()
second_title: Aspose.Slides voor C++ API-referentie
description: Zoek vorm op basis van alternatieve tekst in een PPTX-presentatie.
type: docs
weight: 1
url: /nl/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) methode


Zoek vorm op via alternatieve tekst in een PPTX-presentatie.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Gescanste presentatie. |
| altText | [System::String](../../../system/string/) | Alternatieve tekst van een vorm. |

### Retourwaarde

[Shape](../../../aspose.slides/shape/) of null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) methode


Zoek vorm op via alternatieve tekst op een dia in een PPTX-presentatie.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Gescante dia. |
| altText | [System::String](../../../system/string/) | Alternatieve tekst van een vorm. |

### Retourwaarde

[Shape](../../../aspose.slides/shape/) of null.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IShape](../../../aspose.slides/ishape/)
* Klasse [IPresentation](../../../aspose.slides/ipresentation/)
* Klasse [String](../../../system/string/)
* Klasse [SlideUtil](../)
* Klasse [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Naamruimte [Aspose::Slides::Util](../../)
* Bibliotheek [Aspose.Slides](../../../)