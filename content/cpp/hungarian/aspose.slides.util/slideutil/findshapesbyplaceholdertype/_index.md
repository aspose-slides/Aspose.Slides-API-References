---
title: FindShapesByPlaceholderType()
second_title: Aspose.Slides C++ API hivatkozás
description: Kikeresi a megadott dián az összes alakzatot, amely megfelel a megadott placeholder típusnak.
type: docs
weight: 14
url: /hu/aspose.slides.util/slideutil/findshapesbyplaceholdertype/
---
## SlideUtil::FindShapesByPlaceholderType(System::SharedPtr\<IBaseSlide\>, PlaceholderType) metódus

Kikeresi a megadott dián az összes alakzatot, amely megfelel a megadott PlaceholderType típusnak.

```cpp
static System::ArrayPtr<System::SharedPtr<IShape>> Aspose::Slides::Util::SlideUtil::FindShapesByPlaceholderType(System::SharedPtr<IBaseSlide> slide, PlaceholderType placeholderType)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | A dia, ahol az alakzatok keresése történik. |
| placeholderType | [PlaceholderType](../../../aspose.slides/placeholdertype/) | A placeholder típusa, amely alapján szűri az alakzatokat. |

### Visszatérési érték

Egy [IShape](../../../aspose.slides/ishape/) objektumok tömbje, amely megfelel a megadott PlaceholderType típusnak.

## Lásd még

* Enum [PlaceholderType](../../../aspose.slides/placeholdertype/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Class [SlideUtil](../)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)