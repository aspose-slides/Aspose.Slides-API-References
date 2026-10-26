---
title: InsertClone()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vloží kopii specifikovaného rozložení snímku na určenou pozici ve sbírce.
type: docs
weight: 14
url: /cs/aspose.slides/masterlayoutslidecollection/insertclone/
---
## MasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metoda

Vloží kopii specifikovaného rozložení snímku na určenou pozici ve sbírce.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) ke klonování. |

### Návratová hodnota

Vložený snímek.

## Poznámky

Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto kolekci snímků rozložení. Takže se jedná o ekvivalent kopírování/vkládání s volbou \"Use Destination Theme\" v PowerPointu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [MasterLayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)