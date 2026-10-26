---
title: InsertClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vloží kopii zadaného rozložení snímku na určenou pozici v kolekci.
type: docs
weight: 14
url: /cs/aspose.slides/imasterlayoutslidecollection/insertclone/
---
## IMasterLayoutSlideCollection::InsertClone(int32_t, System::SharedPtr\<ILayoutSlide\>) metoda

Vloží kopii zadaného rozložení snímku na určenou pozici v kolekci.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::InsertClone(int32_t index, System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) ke klonování. |

### Návratová hodnota

Vložený snímek.

## Poznámky

Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto kolekci rozložení snímků. Jedná se tak o ekvivalent kopírování/vkládání s volbou \"Use Destination Theme\" v PowerPointu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [IMasterLayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)