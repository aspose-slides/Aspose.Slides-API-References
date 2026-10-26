---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven dia toe aan het einde van de collectie.
type: docs
weight: 14
url: /nl/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) methode

Voegt een kopie van een opgegeven dia toe aan het einde van de collectie.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |

### Retourwaarde

Nieuwe dia.

## Opmerkingen

Bij het klonen van een dia tussen verschillende presentaties kan de master van de dia ook worden gekloond. Een intern register wordt gebruikt om automatisch gekloonde masters bij te houden om het maken van meerdere klonen van dezelfde masterdia te voorkomen. Handmatig klonen van masterdia's zal noch worden voorkomen noch worden geregistreerd. Als u meer controle over het kloonproces nodig hebt, gebruik dan [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) of [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) voor het klonen van dia's, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) of [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) voor het klonen van lay-outs en [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) voor het klonen van masters.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) methode

Voegt een kopie van een opgegeven dia toe aan het einde van de opgegeven sectie.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) voor een nieuwe dia. |

### Retourwaarde

Nieuwe dia.

## Opmerkingen

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Nu bevat de tweede sectie een kopie van de eerste dia.
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) methode

Voegt een kopie van een opgegeven dia toe aan het einde van de collectie.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layoutdia voor een nieuwe dia. |

### Retourwaarde

Nieuwe dia.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) methode

Voegt een kopie van een opgegeven bron-dia toe aan het einde van de collectie. De juiste lay-out wordt automatisch geselecteerd uit de opgegeven master (de juiste lay-out is de lay-out met hetzelfde Type of dezelfde Naam als de lay-out van de bron-dia). Als er geen juiste lay-out is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout false is).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterdia voor een nieuwe dia. |
| allowCloneMissingLayout | **bool** | Als er geen juiste lay-out in de opgegeven master is, wordt de lay-out van de bron-dia gekloond (als allowCloneMissingLayout true is) of wordt een PptxEditException gegooid (als allowCloneMissingLayout false is). |

### Retourwaarde

Nieuwe dia.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [ISlideCollection](../)
* Klasse [ISection](../../isection/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)