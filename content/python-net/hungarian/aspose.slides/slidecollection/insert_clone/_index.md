---
title: insert_clone method
second_title: Aspose.Slides a Pythonhoz .NET API hivatkozás
description: 
type: docs
url: /hu/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Beilleszt egy másolatot a megadott diából a gyűjtemény megadott pozíciójába.

### Visszatérési érték

Beillesztett dia.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az új dia indexe. |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Másolandó dia. |

### Megjegyzés

Különböző bemutatók közötti dia klónozása esetén a dia mesterét is klónozhatja.
Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** or
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides and
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Beilleszt egy másolatot a megadott diából a gyűjtemény megadott pozíciójába.

### Visszatérési érték

Beillesztett dia.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az új dia indexe. |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Másolandó dia. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Elrendezési dia az új diához. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Beilleszt egy másolatot a megadott forrásdiai a gyűjtemény megadott pozíciójába.
Appropriate layout will be selected automatically from the specified 
master (appropriate layout is the layout with the same Type or Name as 
of layout of the source slide). If there is no appropriate layout then
layout of the source slide will be cloned (if allowCloneMissingLayout 
is true) or PptxEditException will be thrown (if allowCloneMissingLayout
is false).

### Visszatérési érték

Beillesztett dia.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Az új dia indexe. |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Másolandó dia. |
| dest_master | [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide) | Mesterdia az új dia számára. |
| allow_clone_missing_layout | **bool** | Ha a megadott mesterben nincs megfelelő elrendezés, akkor a forrás dia <br/><br/>            elrendezése klónozódik (ha az allowCloneMissingLayout igaz), vagy <br/><br/>            PptxEditException keletkezik (ha az allowCloneMissingLayout hamis). |

### Kivételek

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Kivétel, ha a megadott mesterben nincs megfelelő elrendezés, és <br/>            az allowCloneMissingLayout hamis. |



### Lásd még
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* osztály [`SlideCollection`](/slides/python-net/hu/aspose.slides/slidecollection)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)