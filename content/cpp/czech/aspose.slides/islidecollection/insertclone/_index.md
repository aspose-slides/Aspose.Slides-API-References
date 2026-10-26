---
title: InsertClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vloží kopii zadaného snímku na určenou pozici ve sbírce.
type: docs
weight: 27
url: /cs/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) metoda


Vloží kopii určeného snímku na zadanou pozici ve sbírce.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |

### Návratová hodnota

Vložený snímek.

## Poznámky



Při klonování snímku mezi různými prezentacemi může být klonován také master snímku. Interní registr se používá k sledování automaticky klonovaných masterů, aby se zabránilo vytvoření více kopií stejného master snímku. Ruční klonování master snímků nebude ani zabráněno, ani registrováno. Pokud potřebujete větší kontrolu nad procesem klonování, použijte [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) nebo [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) pro klonování snímků a [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) pro klonování masterů. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metoda


Vloží kopii určeného snímku na zadanou pozici ve sbírce.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Rozvržení snímku pro nový snímek. |

### Návratová hodnota

Vložený snímek.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metoda


Vloží kopii určeného zdrojového snímku na zadanou pozici ve sbírce. Vhodné rozvržení bude vybráno automaticky ze zadaného masteru (vhodné rozvržení je rozvržení se stejným Type nebo Name jako rozvržení zdrojového snímku). Pokud v zadaném masteru neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master snímek pro nový snímek. |
| allowCloneMissingLayout | **bool** | Pokud v zadaném masteru neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false). |

### Návratová hodnota

Vložený snímek.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlide](../../islide/)
* Třída [ISlideCollection](../)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [IMasterSlide](../../imasterslide/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)