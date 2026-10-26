---
title: AddClone()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá kopii zadaného snímku vzhledu do prezentace.
type: docs
weight: 1
url: /cs/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metoda

Přidá kopii zadaného snímku vzhledu do prezentace.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) ke klonování. |

### Návratová hodnota

Přidaný snímek.

## Poznámky

Při klonování vzhledu mezi různými prezentacemi lze také klonovat hlavní snímek vzhledu, aby se zachovalo formátování zdroje. Interní registr se používá ke sledování automaticky klonovaných hlavních snímků, aby se zabránilo vytvoření více klonů stejného hlavního snímku. Ruční klonování hlavních snímků nebude ani zabráněno, ani registrováno.

## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) metoda

Přidá kopii zadaného snímku vzhledu do prezentace.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) ke klonování. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Hlavní snímek pro nový vzhled. |

### Návratová hodnota

Přidaný snímek.

## Poznámky

Nový vzhled bude propojen s definovaným hlavním snímkem v cílové prezentaci. Tedy se jedná o analogii kopírování/vkládání s možností „Use Destination Theme“ v PowerPointu.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [IGlobalLayoutSlideCollection](../)
* Třída [IMasterSlide](../../imasterslide/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)