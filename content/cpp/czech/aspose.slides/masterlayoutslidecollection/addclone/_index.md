---
title: AddClone()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Přidá kopii zadaného snímku rozložení na konec kolekce.
type: docs
weight: 1
url: /cs/aspose.slides/masterlayoutslidecollection/addclone/
---
## MasterLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metoda

Přidá kopii zadaného snímku rozložení na konec kolekce.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::MasterLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) k naklonování. |

### Návratová hodnota

Přidaný snímek.

## Poznámky

1) Nové rozložení bude propojeno s nadřazeným hlavním snímkem pro tuto kolekci snímků rozložení. Takže jde o ekvivalent kopírování/vkládání s možností „Use Destination Theme“ v PowerPointu. 2) Ekvivalent této metody je metoda [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) přístupná přes vlastnost [IPresentation::get_LayoutSlides()](../../ipresentation/get_layoutslides/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [MasterLayoutSlideCollection](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)