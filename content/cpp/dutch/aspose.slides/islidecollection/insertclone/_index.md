---
title: InsertClone()
second_title: Aspose.Slides voor C++ API Referentie
description: Voegt een kopie van een opgegeven dia toe aan een opgegeven positie in de collectie.
type: docs
weight: 27
url: /nl/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) methode


Voegt een kopie van een opgegeven dia toe aan een opgegeven positie in de collectie.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van nieuwe dia. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) om te klonen. |

### Retourwaarde

Ingevoegde dia.
## Opmerkingen



Bij het klonen van een dia tussen verschillende presentaties kan de master van de dia ook worden gekloond. Er wordt een interne register gebruikt om automatisch gekloonde masters bij te houden om te voorkomen dat er meerdere clones van dezelfde masterdia worden gemaakt. Handmatig klonen van masterdia's wordt noch voorkomen noch geregistreerd. Als u meer controle over het kloonproces nodig heeft, gebruik dan [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) of [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) voor het klonen van dia's en [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) voor het klonen van masters. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) methode


Voegt een kopie van een opgegeven dia toe aan een opgegeven positie in de collectie.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van nieuwe dia. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) om te klonen. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layoutdia voor een nieuwe dia. |

### Retourwaarde

Ingevoegde dia.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) methode


Voegt een kopie van een opgegeven bron-dia toe aan een opgegeven positie in de collectie. Een passende lay-out wordt automatisch geselecteerd uit de opgegeven master (een passende lay-out is de lay-out met hetzelfde Type of Naam als de lay-out van de bron-dia). Als er geen passende lay-out is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout false is).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van nieuwe dia. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) om te klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterdia voor een nieuwe dia. |
| allowCloneMissingLayout | **bool** | Als er geen passende lay-out in de opgegeven master is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt PptxEditException gegooid (als allowCloneMissingLayout false is). |

### Retourwaarde

Ingevoegde dia.

## Zie Ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [ISlideCollection](../)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)