---
title: AddClone()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá kopii určeného snímku rozvržení do prezentace.
type: docs
weight: 1
url: /cs/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metoda

Přidá kopii určeného snímku rozvržení do prezentace.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) k naklonování. |

### Návratová hodnota

Přidaný snímek.

## Poznámky

Když se klonuje rozvržení mezi různými prezentacemi, může být také klonován hlavní snímek rozvržení, aby se zachovalo formátování zdroje. Interní registr se používá k sledování automaticky klonovaných hlavních snímků, aby se zabránilo vytvoření několika kopií stejného hlavního snímku. Ruční klonování hlavních snímků nebude ani zabráněno, ani registrováno.

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) metoda

Přidá kopii určeného snímku rozvržení do prezentace.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) k naklonování. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Hlavní snímek pro nové rozvržení. |

### Návratová hodnota

Přidaný snímek.

## Poznámky

1) Nové rozvržení bude spojeno s definovaným hlavním snímkem v cílové prezentaci. Jedná se tedy o ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu. 2) Ekvivalentní metoda je metoda [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) přístupná přes vlastnost [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [GlobalLayoutSlideCollection](../)
* Třída [IMasterSlide](../../imasterslide/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)