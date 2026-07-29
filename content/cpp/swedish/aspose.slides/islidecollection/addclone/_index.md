---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en specificerad bild i slutet av samlingen.
type: docs
weight: 14
url: /sv/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) method

Lägger till en kopia av en specificerad bild i slutet av samlingen.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Ny bild.

## Anmärkningar

När en bild klonas mellan olika presentationer kan bildens master också klonas. Ett internt register används för att spåra automatiskt klonade masterbilder för att förhindra skapandet av flera kloner av samma masterbild. Manuell kloning av masterbilder kommer varken att hindras eller registreras. Om du behöver mer kontroll över kloningsprocessen, använd [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) eller [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) för att klona bilder, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) eller [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) för att klona layouter och [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) för att klona masterbilder.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) method

Lägger till en kopia av en specificerad bild i slutet av den angivna sektionen.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) för en ny bild. |

### Returvärde

Ny bild.

## Anmärkningar

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Nu innehåller den andra sektionen en kopia av den första bilden.
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

Lägger till en kopia av en specificerad bild i slutet av samlingen.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout-bild för en ny bild. |

### Returvärde

Ny bild.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

Lägger till en kopia av en specificerad källbild i slutet av samlingen. Passande layout kommer att väljas automatiskt från den specificerade master (passande layout är den layout som har samma Type eller Name som layouten för källbilden). Om det inte finns någon passande layout kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master-bild för en ny bild. |
| allowCloneMissingLayout | **bool** | Om det inte finns någon passande layout i den specificerade masteren så kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false). |

### Returvärde

Ny bild.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [ISlideCollection](../)
* Klass [ISection](../../isection/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [IMasterSlide](../../imasterslide/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)