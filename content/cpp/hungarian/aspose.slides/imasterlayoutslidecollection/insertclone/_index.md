---
title: InsertClone()
second_title: Aspose.Slides C++ API Referenciája
description: Beszúr egy másolatot egy megadott elrendezési diából a gyűjtemény megadott pozíciójába.
type: docs
weight: 14
url: /hu/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metódus

Beszúr egy másolatot a megadott elrendezési diából a gyűjtemény megadott pozíciójába.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) a klónozandó. |

### Visszatérési érték

Beszúrt dia.

## Megjegyzés

Az új elrendezés a szülő mesterdiával lesz összekapcsolva ebben az elrendezési diák gyűjteményben. Ez tehát a PowerPoint \"Használd a cél témát\" opcióval történő másolás/beillesztés analógja.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)