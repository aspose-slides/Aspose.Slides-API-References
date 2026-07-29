---
title: AddClone()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till en kopia av en specificerad layoutbild i presentationen.
type: docs
weight: 1
url: /sv/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metod

Lägger till en kopia av en specificerad layoutbild i presentationen.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Tillagd bild.
## Anmärkningar



När en layout klonas mellan olika presentationer kan layoutens master också klonas för att behålla källformatet. Ett internt register används för att spåra automatiskt klonade masters för att förhindra skapandet av flera kloner av samma masterbild. Manuell kloning av masterbilder kommer varken att hindras eller registreras. 
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) metod

Lägger till en kopia av en specificerad layoutbild i presentationen.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) att klona. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Masterbild för en ny layout. |

### Returvärde

Tillagd bild.
## Anmärkningar



1) Den nya layouten kommer att länkas till den definierade masteren i målpresentationen. Så detta är motsvarande kopiera/klistra in med "Use Destination Theme"-alternativet i PowerPoint. 2) Motsvarigheten till denna metod är metoden [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) som nås via egenskapen [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/). 
## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [GlobalLayoutSlideCollection](../)
* Klass [IMasterSlide](../../imasterslide/)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)