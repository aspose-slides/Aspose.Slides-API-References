---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Infogar en kopia av en angiven bild på en specificerad position i samlingen.
type: docs
weight: 66
url: /sv/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) metod


Infogar en kopia av en angiven bild på en specificerad position i samlingen.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Infogad bild.

## Anmärkningar



När du klonar en bild mellan olika presentationer kan bildens master också klonas. Intern register används för att spåra automatiskt klonade masters för att förhindra skapandet av flera kloner av samma masterbild. Manuell kloning av masterbilder kommer varken att hindras eller registreras. Om du behöver mer kontroll över kloningsprocessen använd [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) eller [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) för att klona bilder och [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) för att klona masters. 


Följande exempel visar hur du klonar till en annan position inom [Presentation](../../presentation/). 
```cpp
// Instansiera Presentation-klassen som representerar en presentationsfil
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Klona den önskade bilden till slutet av samlingen av bilder i samma presentation
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Klona den önskade bilden till det angivna indexet i samma presentation
slides->InsertClone(2, slides->idx_get(1));
// Skriv den modifierade presentationen till disk
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
Följande exempel visar hur du klonar till en annan position inom [Presentation](../../presentation/). 
```cpp
// Instansiera Presentation-klassen för att läsa in källpresentationsfilen
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Instansiera Presentation-klassen för destinations-PPTX (där bilden ska klonas)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Skriv destinationspresentationen till disk
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metod


Infogar en kopia av en angiven bild på en specificerad position i samlingen.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layoutbild för en ny bild. |

### Returvärde

Infogad bild.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metod


Infogar en kopia av en angiven källbild till en specificerad position i samlingen. Lämplig layout väljs automatiskt från den angivna mastern (lämplig layout är den layout som har samma Typ eller Namn som layouten för källbilden). Om det inte finns någon lämplig layout kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterbild för en ny bild. |
| allowCloneMissingLayout | **bool** | Om det inte finns någon lämplig layout i angiven master kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas PptxEditException (om allowCloneMissingLayout är false). |

### Returvärde

Infogad bild.

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [SlideCollection](../)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [IMasterSlide](../../imasterslide/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)