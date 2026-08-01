---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een gespecificeerde lay-out dia toe aan de presentatie.
type: docs
weight: 1
url: /nl/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) method


Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) om te klonen. |

### Retourwaarde

Toegevoegde dia.
## Opmerkingen



Wanneer een lay-out tussen verschillende presentaties wordt gekloond, kan de master van de lay-out ook worden gekloond om de opmaak van de bron te behouden. Er wordt een intern register gebruikt om automatisch gekloonde masters bij te houden en te voorkomen dat meerdere klonen van dezelfde masterdia worden aangemaakt. Handmatig klonen van masterdia's wordt noch voorkomen noch geregistreerd. 
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) method


Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) om te klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterdia voor een nieuwe lay-out. |

### Retourwaarde

Toegevoegde dia.
## Opmerkingen



Nieuwe lay-out wordt gekoppeld aan de gedefinieerde master in de doelpresentatie. Dit is dus een analogon van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint. 
## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IGlobalLayoutSlideCollection](../)
* Klasse [IMasterSlide](../../imasterslide/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)