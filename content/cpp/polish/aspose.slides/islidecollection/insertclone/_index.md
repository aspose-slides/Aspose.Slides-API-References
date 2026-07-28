---
title: InsertClone()
second_title: Aspose.Slides for C++ Referencja API
description: Wstawia kopię określonego slajdu na podaną pozycję w kolekcji.
type: docs
weight: 27
url: /pl/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) method


Wstawia kopię określonego slajdu na podaną pozycję w kolekcji.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |

### Wartość zwracana

Wstawiony slajd.

## Uwagi



Podczas klonowania slajdu pomiędzy różnymi prezentacjami, master slajdu może zostać również sklonowany. Wewnętrzny rejestr jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu kopii tego samego master slajdu. Ręczne klonowanie master slajdów nie będzie ani zapobiegane, ani rejestrowane. Jeśli potrzebujesz większej kontroli nad procesem klonowania, użyj [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) lub [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) do klonowania slajdów oraz [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) do klonowania masterów. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method


Wstawia kopię określonego slajdu na podaną pozycję w kolekcji.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout slide for a new slide. |

### Wartość zwracana

Wstawiony slajd.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method


Wstawia kopię określonego slajdu źródłowego na podaną pozycję w kolekcji. Odpowiedni układ zostanie automatycznie wybrany z określonego mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout ma wartość true), w przeciwnym razie zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout ma wartość false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| index | **int32_t** | Indeks nowego slajdu. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) do sklonowania. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide for a new slide. |
| allowCloneMissingLayout | **bool** | Jeśli w określonym masterze nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout ma wartość true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout ma wartość false). |

### Wartość zwracana

Wstawiony slajd.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [ISlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)