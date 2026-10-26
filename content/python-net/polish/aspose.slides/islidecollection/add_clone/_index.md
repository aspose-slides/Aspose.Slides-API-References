---
title: add_clone method
second_title: Aspose.Slides dla Pythona – odniesienie API .NET
description: 
type: docs
url: /pl/aspose.slides/islidecollection/add_clone/
weight: 10
---
## add_clone(self, source_slide) {#islide}
Dodaje kopię określonego slajdu na koniec kolekcji.

### Returns

Nowy slajd.



```python
def add_clone(self, source_slide):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |

### Remarks

Podczas klonowania slajdu pomiędzy różnymi prezentacjami można również sklonować master slajdu.
            Rejestr wewnętrzny jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu 
            wielu klonów tego samego master slajdu.
            Ręczne klonowanie master slajdów nie będzie ani zapobiegane, ani rejestrowane.
            Jeśli potrzebujesz większej kontroli nad procesem klonowania, użyj
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slide** lub
            **Aspose.Slides.ISlideCollection.AddClone(Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** do klonowania slajdów,
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slide** lub
            **Aspose.Slides.IGlobalLayoutSlideCollection.AddClone(Aspose.Slides.ILayoutSlide,Aspose.Slide** do klonowania układów i
            **Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** do klonowania masterów.


## add_clone(self, source_slide, section) {#islide-isection}
Dodaje kopię określonego slajdu na koniec określonej sekcji.

### Returns

Nowy slajd.



```python
def add_clone(self, source_slide, section):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |
| section | [`ISection`](/slides/python-net/pl/aspose.slides/isection) | Sekcja dla nowego slajdu. |

### Exceptions

| Wyjątek | Opis |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** |  |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) |  |


## add_clone(self, source_slide, dest_layout) {#islide-ilayoutslide}
Dodaje kopię określonego slajdu na koniec kolekcji.

### Returns

Nowy slajd.



```python
def add_clone(self, source_slide, dest_layout):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Układ slajdu dla nowego slajdu. |


## add_clone(self, source_slide, dest_master, allow_clone_missing_layout) {#islide-imasterslide-bool}
Dodaje kopię określonego slajdu źródłowego na koniec kolekcji.
            Odpowiedni układ zostanie wybrany automatycznie z określonego
            mastera (odpowiedni układ to układ o tym samym Typie lub Nazwie co
            układ slajdu źródłowego). Jeśli nie ma odpowiedniego układu,
            układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout
            jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout
            jest false).

### Returns

Nowy slajd.



```python
def add_clone(self, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |
| dest_master | [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide) | Master slajdu dla nowego slajdu. |
| allow_clone_missing_layout | **bool** | Jeśli w określonym masterze nie ma odpowiedniego układu, układ slajdu źródłowego zostanie sklonowany (jeśli allowCloneMissingLayout jest true) lub zostanie rzucony PptxEditException (jeśli allowCloneMissingLayout jest false). |

### Exceptions

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Rzucony, jeśli w określonym masterze nie ma odpowiedniego układu i
            allowCloneMissingLayout jest false. |



### See Also
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide)
* klasa [`ISection`](/slides/python-net/pl/aspose.slides/isection)
* klasa [`ISlide`](/slides/python-net/pl/aspose.slides/islide)
* klasa [`ISlideCollection`](/slides/python-net/pl/aspose.slides/islidecollection)
* klasa [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)