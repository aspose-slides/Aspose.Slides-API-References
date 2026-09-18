---
title: insert_clone method
second_title: Aspose.Slides a Pythonhoz .NET API-referencia
description: 
type: docs
url: /hu/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Egy megadott dia másolatát illeszti be a gyűjtemény megadott pozíciójába.

### Returns
Inserted slide.

```python
def insert_clone(self, index, source_slide):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Index of new slide. |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Slide to clone. |

### Remarks
Ha egy diát különböző bemutatók között klónozunk, a dia mester is klónozható. Egy belső regiszter használatos az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanannak a mesterdiának több klónjának létrehozását. A mesterdia kézi klónozása sem lesz megakadályozva, sem regisztrálva. Ha nagyobb vezérlést szeretne a klónozási folyamat felett, használja a **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** vagy a **Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** a diák klónozásához, és az **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** a mesterek klónozásához.

## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Egy megadott dia másolatát illeszti be a gyűjtemény megadott pozíciójába.

### Returns
Inserted slide.

```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Index of new slide. |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Slide to clone. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Layout slide for a new slide. |

## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Egy megadott forrásdia másolatát illeszti be a gyűjtemény megadott pozíciójába. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott mesterből (a megfelelő elrendezés az a layout, amelynek típusa vagy neve megegyezik a forrásdia layoutjának típusával vagy nevével). Ha nincs megfelelő elrendezés, akkor a forrásdia layoutja lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis).

### Returns
Inserted slide.

```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```

| Paraméter | Típus | Leírás |
| :- | :- | :- |
| index | **int** | Index of new slide. |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Slide to clone. |
| dest_master | [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide) | Master slide for a new slide. |
| allow_clone_missing_layout | **bool** | If there is no appropriate layout in specified master then layout of the <br/><br/>            source slide will be cloned (if allowCloneMissingLayout is true) or <br/><br/>            PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Exceptions
| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Dobott, ha a megadott mesterben nincs megfelelő elrendezés, és <br/>            allowCloneMissingLayout is false. |

### See Also
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`ISlideCollection`](/slides/python-net/hu/aspose.slides/islidecollection)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)