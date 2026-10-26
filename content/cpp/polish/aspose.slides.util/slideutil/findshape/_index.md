---
title: FindShape()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Znajdź kształt po alternatywnym tekście w prezentacji PPTX.
type: docs
weight: 1
url: /pl/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) method


Znajdź kształt po alternatywnym tekście w prezentacji PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Przeskanowana prezentacja. |
| altText | [System::String](../../../system/string/) | Alternatywny tekst kształtu. |

### Wartość zwracana

[Shape](../../../aspose.slides/shape/) or null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) method


Znajdź kształt po alternatywnym tekście na slajdzie w prezentacji PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Przeskanowany slajd. |
| altText | [System::String](../../../system/string/) | Alternatywny tekst kształtu. |

### Wartość zwracana

[Shape](../../../aspose.slides/shape/) or null.

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IShape](../../../aspose.slides/ishape/)
* Klasa [IPresentation](../../../aspose.slides/ipresentation/)
* Klasa [String](../../../system/string/)
* Klasa [SlideUtil](../)
* Klasa [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Przestrzeń nazw [Aspose::Slides::Util](../../)
* Biblioteka [Aspose.Slides](../../../)