---
title: add_clone method
second_title: Aspose.Slides Python számára .NET API referencia
description: 
type: docs
url: /hu/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Hozzáad egy megadott dia másolatát a gyűjtemény végéhez.

### Returns

Új dia.



```python
def add_clone(self, source_slide):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Klónozandó dia. |

### Remarks

Dia klónozása során különböző bemutatók között a dia mestere is klónozható.
            Belső nyilvántartás használatos az automatikusan klónozott mesterek nyomon követésére, hogy elkerüljük 
            ugyanazon mester dia több klónjának létrehozását.
            A mester diák manuális klónozása sem nem lesz meggátolva, sem nyilvántartva.
            Ha nagyobb ellenőrzésre van szükség a klónozási folyamatban, használja a
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** vagy
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** a dia klónozásához,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** vagy
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** az elrendezések klónozásához,
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** a mesterek klónozásához.


## add_clone(self, source_slide, section) {#islide-isection}
Hozzáad egy megadott dia másolatát a megadott szekció végéhez.

### Returns

Új dia.



```python
def add_clone(self, source_slide, section):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Klónozandó dia. |
| section | [`ISection`](/slides/python-net/hu/aspose.slides/isection) | Új dia szekciója. |

### Exceptions

| Kivétel | Leírás |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Hozzáad egy megadott dia másolatát a gyűjtemény végéhez.

### Returns

Új dia.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Klónozandó dia. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide) | Új dia elrendezése. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Hozzáad egy megadott forrás diát a gyűjtemény végéhez.
            A megfelelő elrendezés automatikusan ki lesz választva a megadott 
            mesterből (a megfelelő elrendezés az a layout, amelynek típusa vagy neve megegyezik a forrás dia elrendezésével). Ha nincs megfelelő elrendezés,
            a forrás dia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy 
            PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis).

### Returns

Új dia.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Paraméter | Típus | Leírás |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/hu/aspose.slides/islide) | Klónozandó dia. |
| dest_master | [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide) | Új dia mesterdiai. |
| allow_clone_missing_layout | **bool** | Ha a megadott mesterben nincs megfelelő elrendezés, akkor a <br/><br/>            forrás dia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy <br/><br/>            PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis). |

### Exceptions

| Kivétel | Leírás |
| :- | :- |
| [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception) | Dobva, ha a megadott mesterben nincs megfelelő elrendezés és <br/>            az allowCloneMissingLayout hamis. |



### See Also
* osztály [`ILayoutSlide`](/slides/python-net/hu/aspose.slides/ilayoutslide)
* osztály [`IMasterSlide`](/slides/python-net/hu/aspose.slides/imasterslide)
* osztály [`ISection`](/slides/python-net/hu/aspose.slides/isection)
* osztály [`ISlide`](/slides/python-net/hu/aspose.slides/islide)
* osztály [`ISlideCollection`](/slides/python-net/hu/aspose.slides/islidecollection)
* osztály [`PptxEditException`](/slides/python-net/hu/aspose.slides/pptxeditexception)
* modul [`aspose.slides`](/slides/python-net/hu/aspose.slides)
* könyvtár [`Aspose.Slides`](/slides/python-net)