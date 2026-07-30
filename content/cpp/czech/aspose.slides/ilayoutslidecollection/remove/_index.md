---
title: Remove()
second_title: Aspose.Slides pro C++ referenční příručka API
description: Odstraní rozvržení ze sbírky.
type: docs
weight: 27
url: /cs/aspose.slides/ilayoutslidecollection/remove/
---
## ILayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) metoda

Odstraní rozvržení ze sbírky.

```cpp
virtual void Aspose::Slides::ILayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Rozvržení snímku, které se má odstranit ze sbírky. |

## Poznámky

1) Aby se předešlo vyhození výjimky PptxEditException, zkontrolujte předem vlastnost HasDependingSlides rozvržení. 2) Můžete také použít metodu [ILayoutSlide::Remove](../../ilayoutslide/remove/) k zjednodušení kódu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [ILayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)