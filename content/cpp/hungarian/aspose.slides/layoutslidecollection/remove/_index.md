---
title: Remove()
second_title: Aspose.Slides for C++ API Referenciája
description: Eltávolít egy elrendezést a gyűjteményből.
type: docs
weight: 66
url: /hu/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) method

Eltávolít egy elrendezést a gyűjteményből.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```

### Arguments

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Az eltávolítandó elrendezés csúszka a gyűjteményből. |

## Megjegyzések

1) Az PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előre. 2) A kód egyszerűsítéséhez használhatja a [ILayoutSlide::Remove](../../ilayoutslide/remove/) metódust is. 

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ILayoutSlide](../../ilayoutslide/)
* Osztály [LayoutSlideCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)