---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en specificerad bild i slutet av samlingen.
type: docs
weight: 53
url: /sv/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) metod

Lägger till en kopia av en specificerad bild i slutet av samlingen.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Ny bild.

## Anmärkningar

När du klonar en bild mellan olika presentationer kan bildens master också klonas. Ett internt register används för att spåra automatiskt klonade mastrar för att förhindra skapandet av flera kloner av samma masterbild. Manuell kloning av masterbilder kommer varken att förhindras eller registreras. Om du behöver mer kontroll över kloningsprocessen, använd [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) eller [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) för att klona bilder, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) eller [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) för att klona layouter och [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) för att klona masterbilder.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metod

Lägger till en kopia av en specificerad bild i slutet av den specificerade sektionen.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
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

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metod

Lägger till en kopia av en specificerad bild i slutet av samlingen.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layoutbild för en ny bild. |

### Returvärde

Ny bild.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metod

Lägger till en kopia av en specificerad källbild i slutet av samlingen. Lämplig layout kommer att väljas automatiskt från den specificerade mastern (lämplig layout är den layout som har samma Type eller Name som layouten för källbilden). Om det inte finns någon lämplig layout så kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kommer PptxEditException att kastas (om allowCloneMissingLayout är false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterbild för en ny bild. |
| allowCloneMissingLayout | **bool** | Om det inte finns någon lämplig layout i den specificerade mastern så kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kommer PptxEditException att kastas (om allowCloneMissingLayout är false). |

### Returvärde

Ny bild.

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [SlideCollection](../)
* Klass [ISection](../../isection/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [IMasterSlide](../../imasterslide/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)