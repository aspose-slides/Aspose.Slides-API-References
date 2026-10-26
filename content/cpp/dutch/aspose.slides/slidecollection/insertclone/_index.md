---
title: InsertClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven dia toe op de opgegeven positie van de collectie.
type: docs
weight: 66
url: /nl/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) methode


Voegt een kopie van een opgegeven dia toe op de opgegeven positie van de collectie.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van de nieuwe dia. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |

### Return Value

Toegevoegde dia.
## Opmerkingen



Wanneer een dia tussen verschillende presentaties wordt gekloond, kan ook de master van de dia worden gekloond. Een intern register wordt gebruikt om automatisch gekloonde masters bij te houden om het aanmaken van meerdere klonen van dezelfde masterdia te voorkomen. Handmatig klonen van masterdia's wordt noch voorkomen noch geregistreerd. Als u meer controle over het kloonproces nodig heeft, gebruik dan [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) of [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) voor het klonen van dia's en [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) voor het klonen van masters. 


Het volgende voorbeeld toont hoe te klonen naar een andere positie binnen [Presentation](../../presentation/). 
```cpp
// Maak een Presentation klasse die een presentatiebestand representeert
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Kloon de gewenste dia naar het einde van de collectie dia's in dezelfde presentatie
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Kloon de gewenste dia naar de opgegeven index in dezelfde presentatie
slides->InsertClone(2, slides->idx_get(1));
// Schrijf de gewijzigde presentatie naar schijf
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 Het volgende voorbeeld toont hoe te klonen naar een andere positie binnen [Presentation](../../presentation/). 
```cpp
// Instantieer Presentation-klasse om het bronpresentatiebestand te laden
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Instantieer Presentation-klasse voor de bestemmings-PPTX (waar de dia gekloond moet worden)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Schrijf de bestemmingspresentatie naar schijf
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) methode


Voegt een kopie van een opgegeven dia toe op de opgegeven positie van de collectie.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van de nieuwe dia. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Lay-outdia voor een nieuwe dia. |

### Return Value

Toegevoegde dia.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) methode


Voegt een kopie van een opgegeven bron-dia toe op de opgegeven positie van de collectie. Een geschikt lay-out wordt automatisch geselecteerd uit de opgegeven master (een geschikt lay-out is de lay-out met hetzelfde Type of dezelfde Naam als de lay-out van de bron-dia). Als er geen geschikt lay-out bestaat, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout false is).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Arguments

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | **int32_t** | Index van de nieuwe dia. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterdia voor een nieuwe dia. |
| allowCloneMissingLayout | **bool** | Als er geen geschikt lay-out in de opgegeven master is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout false is). |

### Return Value

Toegevoegde dia.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [SlideCollection](../)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Naamruimte [Aspose::Slides](../../)
* Bibliotheek [Aspose.Slides](../../../)