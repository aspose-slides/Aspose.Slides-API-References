---
title: insert_clone method
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/islidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Wstawia kopię określonego slajdu w określonej pozycji kolekcji.

### Zwraca

Wstawiony slajd.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |

### Uwagi

Podczas klonowania slajdu między różnymi prezentacjami, master slajdu może być również sklonowany.
Internal registry is used to track automatically cloned masters to prevent creation of multiple clones of the same master slide.
Manual cloning of master slides will be neither prevented nor registered.
If you need more control over cloning process use
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** or
**Aspose.Slides.ISlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** for cloning slides and
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** for cloning masters.


## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Wstawia kopię określonego slajdu w określonej pozycji kolekcji.

### Zwraca

Wstawiony slajd.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Układ slajdu dla nowego slajdu. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Wstawia kopię określonego slajdu źródłowego w określonej pozycji kolekcji.
Appropriate layout will be selected automatically from the specified 
master (appropriate layout is the layout with the same Type or Name as 
of layout of the source slide). If there is no appropriate layout then
layout of the source slide will be cloned (if allowCloneMissingLayout 
is true) or PptxEditException will be thrown (if allowCloneMissingLayout
is false).

### Zwraca

Wstawiony slajd.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parameter | Type | Description |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |
| dest_master | [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide) | Master slajdu dla nowego slajdu. |
| allow_clone_missing_layout | **bool** | Jeśli w określonym masterze nie ma odpowiedniego układu, zostanie sklonowany układ <br/><br/>            slajdu źródłowego (jeśli allowCloneMissingLayout jest true) lub <br/><br/>            zostanie zgłoszony PptxEditException (jeśli allowCloneMissingLayout jest false). |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucany, jeśli w określonym masterze nie ma odpowiedniego układu i <br/>            allowCloneMissingLayout jest false. |



### Zobacz także
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide)
* klasa [`ISlide`](/slides/python-net/pl/aspose.slides/islide)
* klasa [`ISlideCollection`](/slides/python-net/pl/aspose.slides/islidecollection)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)