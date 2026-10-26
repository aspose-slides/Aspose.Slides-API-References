---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.
type: docs
weight: 1
url: /nl/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) methode

Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) om te klonen. |

### Retourwaarde

Toegevoegde dia.

## Opmerkingen

Bij het klonen van een lay-out tussen verschillende presentaties kan de master van de lay-out ook worden gekloond om de bronopmaak te behouden. Een intern register wordt gebruikt om automatisch gekloonde masters bij te houden en te voorkomen dat meerdere kopieën van dezelfde masterdia worden gemaakt. Handmatig klonen van masterdia's wordt noch voorkomen noch geregistreerd.

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) methode

Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) om te klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterdia voor een nieuwe lay-out. |

### Retourwaarde

Toegevoegde dia.

## Opmerkingen

1) De nieuwe lay-out wordt gekoppeld aan de gedefinieerde master in de doelpresentatie. Dit is dus analoog aan kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint. 2) Analoge van deze methode is methode [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) die wordt benaderd via de eigenschap [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/).

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [GlobalLayoutSlideCollection](../)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)