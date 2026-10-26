---
title: add_clone method
second_title: Aspose.Slides Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Hozzáad egy másolatot a megadott elrendezési diából a bemutatóhoz.

### Visszatérési érték

Hozzáadott dia.



```python
def add_clone(self, source_layout):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Klónozandó dia. |

### Megjegyzés

Amikor egy elrendezést klónozunk különböző bemutatók között, az elrendezés mesterét is lehet klónozni a forrásformázás megtartása érdekében. Belső regisztert használnak az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia több klónjának létrehozását. A mesterdiák kézi klónozása sem lesz megakadályozva, sem nyilvántartva.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Hozzáad egy másolatot a megadott elrendezési diából a bemutatóhoz.

### Visszatérési érték

Hozzáadott dia.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Klónozandó dia. |
| dest_master | [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide) | Mesterdia egy új elrendezéshez. |

### Megjegyzés

Az új elrendezés a meghatározott mesterrel lesz összekapcsolva a célbemutatóban. Ez tehát a másolás/beillesztés analógja a PowerPoint "Use Destination Theme" (Célháttér alkalmazása) opcióval.



### Lásd még
* osztály [`IGlobalLayoutSlideCollection`](/slides/python-net/hu/aspose.slides/igloballayoutslidecollection)
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)