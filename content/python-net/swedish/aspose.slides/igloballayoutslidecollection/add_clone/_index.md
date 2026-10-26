---
title: add_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Lägger till en kopia av en specificerad layout slide till presentationen.

### Returnerar
Tillagd slide.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Slide att klona. |

### Anmärkningar
När du klonar en layout mellan olika presentationer kan layoutens master också klonas för att behålla källformatet. Ett internt register används för att spåra automatiskt klonade masters för att förhindra skapandet av flera kloner av samma master slide. Manuell kloning av master slides kommer varken att förhindras eller registreras.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Lägger till en kopia av en specificerad layout slide till presentationen.

### Returnerar
Tillagd slide.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Slide att klona. |
| dest_master | [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide) | Master slide för en ny layout. |

### Anmärkningar
Ny layout kommer att länkas till definierad master i destinationspresentationen. Så detta är en analogi till kopiera/klistra med "Use Destination Theme"-alternativet i PowerPoint.



### Se även
* class [`IGlobalLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/igloballayoutslidecollection)
* class [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide)
* module [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)