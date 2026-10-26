---
title: FindShapesByPlaceholderType()
second_title: Aspose.Slides för C++ API-referens
description: Söker efter alla former på den specificerade bilden som matchar den angivna platshållartypen.
type: docs
weight: 14
url: /sv/aspose.slides.util/slideutil/findshapesbyplaceholdertype/
---
## SlideUtil::FindShapesByPlaceholderType(System::SharedPtr\<IBaseSlide\>, PlaceholderType) metod

Söker efter alla former på den angivna bilden som matchar den angivna platshållartypen.

```cpp
static System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::Util::SlideUtil::FindShapesByPlaceholderType(System::SharedPtr<IBaseSlide> slide, PlaceholderType placeholderType)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Bilden som ska sökas efter former. |
| placeholderType | [PlaceholderType](../../../aspose.slides/placeholdertype/) | Typen av platshållare att filtrera former efter. |

## Returvärde

En array av [IShape](../../../aspose.slides/ishape/)-objekt som matchar den angivna platshållartypen.

## Se även

* Enum [PlaceholderType](../../../aspose.slides/placeholdertype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [IShape](../../../aspose.slides/ishape/)
* Klass [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Klass [SlideUtil](../)
* Namnrymd [Aspose::Slides::Util](../../)
* Bibliotek [Aspose.Slides](../../../)