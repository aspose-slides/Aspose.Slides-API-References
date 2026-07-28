---
title: InsertClone()
second_title: Aspose.Slides for C++ API referencia
description: Beszúr egy példányt egy megadott elrendezési diából a gyűjtemény meghatározott pozíciójába.
type: docs
weight: 14
url: /hu/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metódus


Beszúr egy példányt a megadott elrendezési diából a gyűjtemény megadott pozíciójába.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klónozandó. |

### Visszatérési érték

Beszúrt dia.
## Megjegyzés

Az új elrendezés a szülő mester diahoz lesz kapcsolva ebben az elrendezési dia gyűjteményben. Ez a PowerPoint \"Use Destination Theme\" opcióval történő másolás/beillesztés analógiája. 

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [MasterLayoutSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)