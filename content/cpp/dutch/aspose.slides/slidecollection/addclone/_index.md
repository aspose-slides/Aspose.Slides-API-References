---
title: AddClone()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt een kopie van een opgegeven dia toe aan het einde van de verzameling.
type: docs
weight: 53
url: /nl/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) methode

Voegt een kopie van een opgegeven dia toe aan het einde van de verzameling.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |

### Retourwaarde

Nieuwe dia.

## Opmerkingen

Bij het klonen van een dia tussen verschillende presentaties kan de master van de dia ook worden gekloond. Een intern register wordt gebruikt om automatisch gekloonde masters bij te houden en te voorkomen dat meerdere exemplaren van dezelfde masterdia worden gemaakt. Handmatig klonen van masterdia's wordt niet voorkomen of geregistreerd. Als u meer controle over het kloonproces nodig heeft, gebruik dan [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) of [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) voor het klonen van dia's, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) of [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) voor het klonen van lay-outs en [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) voor het klonen van masters.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) methode

Voegt een kopie van een opgegeven dia toe aan het einde van de opgegeven sectie.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
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

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) methode

Voegt een kopie van een opgegeven dia toe aan het einde van de verzameling.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layoutdia voor een nieuwe dia. |

### Retourwaarde

Nieuwe dia.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) methode

Voegt een kopie van een opgegeven brondia toe aan het einde van de verzameling. Een geschikte lay-out wordt automatisch geselecteerd uit de opgegeven master (een geschikte lay-out is de lay-out met hetzelfde Type of dezelfde Naam als de lay-out van de brondia). Als er geen geschikte lay-out in de opgegeven master is, wordt de lay-out van de brondia gekloond (als allowCloneMissingLayout waar is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout onwaar).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) te klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterdia voor een nieuwe dia. |
| allowCloneMissingLayout | **bool** | Als er geen geschikte lay-out in de opgegeven master is, wordt de lay-out van de brondia gekloond (als allowCloneMissingLayout waar is) of wordt er een PptxEditException gegooid (als allowCloneMissingLayout onwaar). |

### Retourwaarde

Nieuwe dia.

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [SlideCollection](../)
* Klasse [ISection](../../isection/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Naamruimte [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)