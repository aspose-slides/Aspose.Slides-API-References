---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Infogar en kopia av en angiven master slide till den angivna positionen i samlingen. Länkade layout slides kopieras också.
type: docs
weight: 105
url: /sv/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metod

Infogar en kopia av en angiven master slide till den angivna positionen i samlingen. Länkade layout-slides kopieras också.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för ny slide. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Infogad master slide.

## Anmärkningar

Följande exempel visar hur man klonar en master slide i en annan PowerPoint [Presentation](../../presentation/). 
```cpp
// Instansiera Presentation-klass för att läsa in källpresentationsfilen
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Instansiera Presentation-klass för destinationspresentationen (där bilden ska klonas)
auto destPres = System::MakeObject<Presentation>();

// Instansiera ISlide från samlingen av bilder i källpresentationen tillsammans med
// Master-bild
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Hämta masterbilder för destinationspresentationen
auto masters = destPres->get_Masters();
// Klona den önskade master-bilden från källpresentationen till samlingen av masterbilder i
// destinationspresentationen
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Samling av bilder i destinationspresentationen
auto slides = destPres->get_Slides();
// Klona källbilden till destinationsbildsamlingen.
slides->AddClone(sourceSlide, iSlide, true);
// Spara destinationspresentationen till disk
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [MasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)