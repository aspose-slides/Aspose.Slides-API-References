---
title: add_clone method
second_title: Aspose.Slides a Pythonhoz .NET-en keresztül API referencia
description: 
type: docs
url: /hu/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
A megadott elrendezésdió másolatát adja hozzá a bemutatóhoz.

### Returns
Hozzáadott dia.



```python
def add_clone(self, source_layout):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | A másolandó dia. |

### Remarks
Amikor egy elrendezést különböző bemutatók között klónoznak, a layout mesterét is klónozhatják, hogy megőrizzék a forrás formázását. Egy belső regiszter használatos az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozza ugyanazon mesterdia többszörös klónjának létrehozását. A mesterdiák kézi klónozása sem kerül megakadályozásra, sem kerül nyilvántartásba.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
A megadott elrendezésdió másolatát adja hozzá a bemutatóhoz.

### Returns
Hozzáadott dia.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | A másolandó dia. |
| dest_master | [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide) | Mesterdia egy új elrendezéshez. |

### Remarks
1) Az új elrendezés a célbemutatóban meghatározott mesterhez lesz csatolva.  
   Így ez a PowerPoint „Use Destination Theme” opcióval való másolás/beillesztés analógja.  
2) Ennek a metódusnak az analógja a **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** metódus, amely a [`IMasterSlide.layout_slides`](/slides/python-net/hu/aspose.slides/imasterslide/layout_slides) tulajdonnal érhető el.



### See Also
* osztály [`GlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/globallayoutslidecollection)
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)