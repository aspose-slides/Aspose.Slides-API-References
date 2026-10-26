---
title: Remove()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Odstraňuje rozvržení ze sbírky.
type: docs
weight: 66
url: /cs/aspose.slides/layoutslidecollection/remove/
---
## LayoutSlideCollection::Remove(System::SharedPtr\<ILayoutSlide\>) metoda


Odstraňuje rozvržení ze sbírky.

```cpp
void Aspose::Slides::LayoutSlideCollection::Remove(System::SharedPtr<ILayoutSlide> value) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Rozvržení snímku, které se má odebrat ze sbírky. |
## Poznámky



1) Aby se předešlo vyhození výjimky PptxEditException, předtím zkontrolujte vlastnost HasDependingSlides rozvržení. 2) Můžete také použít metodu [ILayoutSlide::Remove](../../ilayoutslide/remove/) pro zjednodušení kódu. 
## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [LayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)