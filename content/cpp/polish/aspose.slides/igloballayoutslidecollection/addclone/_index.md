---
title: AddClone()
second_title: Aspose.Slides dla C++ – Referencja API
description: Dodaje kopię określonego slajdu układu do prezentacji.
type: docs
weight: 1
url: /pl/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Dodaje kopię określonego slajdu układu do prezentacji.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) do sklonowania. |

### Wartość zwracana

Dodany slajd.
## Uwagi



Podczas klonowania układu między różnymi prezentacjami master układu może zostać również sklonowany, aby zachować formatowanie źródła. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu kopii tego samego slajdu master. Ręczne klonowanie slajdów master nie będzie ani zapobiegane, ani rejestrowane. 
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method


Dodaje kopię określonego slajdu układu do prezentacji.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) do sklonowania. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slajd master dla nowego układu. |

### Wartość zwracana

Dodany slajd.
## Uwagi



Nowy układ zostanie powiązany z określonym masterem w docelowej prezentacji. Jest to więc odpowiednik kopiuj/wklej z opcją „Use Destination Theme” w programie PowerPoint. 
## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [ILayoutSlide](../../ilayoutslide/)
* Klasa [IGlobalLayoutSlideCollection](../)
* Klasa [IMasterSlide](../../imasterslide/)
* Przestrzeń nazw [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)