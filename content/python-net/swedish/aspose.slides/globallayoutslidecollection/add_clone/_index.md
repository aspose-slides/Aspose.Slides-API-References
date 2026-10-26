---
title: add_clone method
second_title: Aspose.Slides för Python via .NET API-referens
description: 
type: docs
url: /sv/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Lägger till en kopia av en specificerad layoutbild i presentationen.

### Returnerar

Tillagd bild.



```python
def add_clone(self, source_layout):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Bild att klona. |

### Anmärkningar

När en layout klonas mellan olika presentationer kan layoutens master också klonas för att behålla källformatet. Ett internt register används för att spåra automatiskt klonade masters för att förhindra skapandet av flera kloner av samma master-bild. Manuell kloning av master-bilder hindras inte och registreras inte.



## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Lägger till en kopia av en specificerad layoutbild i presentationen.

### Returnerar

Tillagd bild.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide) | Bild att klona. |
| dest_master | [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide) | Master-bild för en ny layout. |

### Anmärkningar

1) Ny layout kommer att länkas till definierad master i målpresentationen. Så detta är motsvarigheten till kopiera/klistra med "Use Destination Theme"-alternativet i PowerPoint.  
2) Motsvarigheten till denna metod är metoden **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** åtkomst via [`IMasterSlide.layout_slides`](/slides/python-net/sv/aspose.slides/imasterslide/layout_slides)-egenskapen.



### Se också
* klass [`GlobalLayoutSlideCollection`](/slides/python-net/sv/aspose.slides/globallayoutslidecollection)
* klass [`ILayoutSlide`](/slides/python-net/sv/aspose.slides/ilayoutslide)
* klass [`IMasterSlide`](/slides/python-net/sv/aspose.slides/imasterslide)
* modul [`aspose.slides`](/slides/python-net/sv/aspose.slides)
* bibliotek [`Aspose.Slides`](/slides/python-net)