---
title: add_clone method
second_title: Aspose.Slides Pythonhoz a .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/slidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
A megadott dia másolatát adja a gyűjtemény végéhez.

### Visszatérési érték

Új dia.



```python
def add_clone(self, source_slide):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Slide a klónozáshoz. |

### Megjegyzés

Különböző prezentációk között dia klónozása esetén a dia mestere is klónozható.  
Belső regisztert használnak az automatikusan klónozott masterek nyomon követésére, hogy megakadályozzák ugyanazon master dia többklónjának létrehozását.  
A master diák manuális klónozása sem lesz megakadályozva, sem regisztrálva.  
Ha nagyobb irányítást igényel a klónozási folyamat felett, használja  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** vagy  
**Aspose.Slides.SlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** a diák klónozásához,  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** vagy  
**Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** a layoutek klónozásához, és  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** a masterek klónozásához.


## add_clone(self, source_slide, section) {#islide-isection}
A megadott dia másolatát adja a megadott szakasz végéhez.

### Visszatérési érték

Új dia.



```python
def add_clone(self, source_slide, section):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Slide a klónozáshoz. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | Section egy új dia számára. |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
A megadott dia másolatát adja a gyűjtemény végéhez.

### Visszatérési érték

Új dia.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Slide a klónozáshoz. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Layout slide egy új dia számára. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
A megadott forrásdia másolatát adja a gyűjtemény végéhez.  
A megfelelő elrendezés automatikusan ki lesz választva a megadott masterből (a megfelelő elrendezés az a layout, amelynek ugyanaz a Type vagy Name értéke, mint a forrásdia layoutja). Ha nincs megfelelő elrendezés, akkor a forrásdia layoutja lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException kerül dobásra (ha az allowCloneMissingLayout hamis).

### Visszatérési érték

Új dia.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Slide a klónozáshoz. |
| dest_master | [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide) | Master slide egy új dia számára. |
| allow_clone_missing_layout | **bool** | Ha a megadott masterben nincs megfelelő elrendezés, akkor a <br/><br/> forrásdia layoutja lesz klónozva (ha az allowCloneMissingLayout igaz), vagy <br/><br/> PptxEditException kerül dobásra (ha az allowCloneMissingLayout hamis). |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Dobásra kerül, ha a megadott masterben nincs megfelelő elrendezés és <br/>            az allowCloneMissingLayout hamis. |



### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide)
* osztály [`ISection`](/slides/python-net/hu/aspose.slides/isection)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* osztály [`SlideCollection`](/slides/python-net/hu/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)