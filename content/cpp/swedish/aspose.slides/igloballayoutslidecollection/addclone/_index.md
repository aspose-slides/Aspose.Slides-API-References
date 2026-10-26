---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en angiven layoutbild i presentationen.
type: docs
weight: 1
url: /sv/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metod


Lägger till en kopia av en angiven layoutbild i presentationen.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Tillagd bild.

## Anmärkningar



När man klonar en layout mellan olika presentationer kan layoutens master också klonas för att behålla källformatet. Ett internt register används för att spåra automatiskt klonade masters för att förhindra skapandet av flera kopior av samma masterbild. Manuell kloning av masterbilder kommer varken att förhindras eller registreras. 
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) metod


Lägger till en kopia av en angiven layoutbild i presentationen.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) att klona. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterbild för en ny layout. |

### Returvärde

Tillagd bild.

## Anmärkningar



Den nya layouten kommer att länkas till den definierade masteren i målpresentationen. Så detta är motsvarigheten till kopiera/klistra in med \"Use Destination Theme\"-alternativet i PowerPoint. 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [IGlobalLayoutSlideCollection](../)
* Klass [IMasterSlide](../../imasterslide/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)