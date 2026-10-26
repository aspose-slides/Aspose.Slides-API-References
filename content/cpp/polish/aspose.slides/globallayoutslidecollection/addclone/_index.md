---
title: AddClone()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Dodaje kopię określonego slajdu układu do prezentacji.
type: docs
weight: 1
url: /pl/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method

Dodaje kopię określonego slajdu układu do prezentacji.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) do sklonowania. |

### Wartość zwracana

Dodany slajd.

## Uwagi

Kiedy klonuje się układ między różnymi prezentacjami, master układu może być również sklonowany, aby zachować formatowanie źródła. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu kopii tego samego slajdu master. Ręczne klonowanie masterów slajdów nie będzie ani zapobiegane, ani rejestrowane.

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method

Dodaje kopię określonego slajdu układu do prezentacji.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) do sklonowania. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slajd master dla nowego układu. |

### Wartość zwracana

Dodany slajd.

## Uwagi

1) Nowy układ zostanie powiązany z określonym masterem w docelowej prezentacji. Jest to więc odpowiednik kopiuj/wklej z opcją \"Use Destination Theme\" w PowerPoint. 2) Odpowiednikiem tej metody jest metoda [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) dostępna za pośrednictwem właściwości [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [GlobalLayoutSlideCollection](../)
* Klasa [IMasterSlide](../../imasterslide/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)