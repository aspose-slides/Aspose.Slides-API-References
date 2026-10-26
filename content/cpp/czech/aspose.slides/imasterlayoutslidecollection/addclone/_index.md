---
title: AddClone()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Přidá kopii zadaného rozložení snímku na konec kolekce.
type: docs
weight: 1
url: /cs/aspose.slides/imasterlayoutslidecollection/addclone/
---
## IMasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metoda

Přidá kopii zadaného rozložení snímku na konec kolekce.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IMasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) to clone. |

### Návratová hodnota

Přidaný snímek.

## Poznámky

1) Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto kolekci snímků rozložení. Takže se jedná o analogii kopírování/vkládání s možností \"Use Destination Theme\" v PowerPointu. 2) Analogie této metody je metoda [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) přístupná pomocí vlastnosti [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [IMasterLayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)