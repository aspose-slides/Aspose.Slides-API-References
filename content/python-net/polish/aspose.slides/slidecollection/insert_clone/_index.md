---
title: insert_clone method
second_title: Aspose.Slides dla Pythona przez .NET – odniesienie API
description: 
type: docs
url: /pl/aspose.slides/slidecollection/insert_clone/
weight: 60
---
## insert_clone(self, index, source_slide) {#int-islide}
Wstawia kopię określonego slajdu na podaną pozycję w kolekcji.

### Zwraca

Wstawiony slajd.



```python
def insert_clone(self, index, source_slide):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |

### Uwagi

Podczas klonowania slajdu pomiędzy różnymi prezentacjami master slajdu może być także sklonowany.  
Rejestr wewnętrzny jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu wielu klonów tego samego master-slajdu.  
Ręczne klonowanie master-slajdów nie będzie ani zapobiegane, ani rejestrowane.  
Jeśli potrzebna jest większa kontrola nad procesem klonowania, użyj  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slide** lub  
**Aspose.Slides.SlideCollection.InsertClone(System.Int32,Aspose.Slides.ISlide,Aspose.Slides.IMasterSlide,Syste** dla klonowania slajdów oraz  
**Aspose.Slides.IMasterSlideCollection.AddClone(Aspose.Slide** dla klonowania master-slajdów.



## insert_clone(self, index, source_slide, dest_layout) {#int-islide-ilayoutslide}
Wstawia kopię określonego slajdu na podaną pozycję w kolekcji.

### Zwraca

Wstawiony slajd.



```python
def insert_clone(self, index, source_slide, dest_layout):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |
| dest_layout | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Layout slajdu dla nowego slajdu. |


## insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout) {#int-islide-imasterslide-bool}
Wstawia kopię określonego slajdu źródłowego na podaną pozycję w kolekcji.  
Odpowiedni layout zostanie wybrany automatycznie z podanego mastera (odpowiedni layout to layout o tym samym typie lub nazwie co layout slajdu źródłowego). Jeśli nie ma odpowiedniego layoutu, layout slajdu źródłowego zostanie sklonowany (gdy allowCloneMissingLayout jest prawdziwe) lub zostanie zgłoszony PptxEditException (gdy allowCloneMissingLayout jest fałszywe).

### Zwraca

Wstawiony slajd.



```python
def insert_clone(self, index, source_slide, dest_master, allow_clone_missing_layout):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| index | **int** | Indeks nowego slajdu. |
| source_slide | [`ISlide`](/slides/python-net/pl/aspose.slides/islide) | Slajd do sklonowania. |
| dest_master | [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide) | Master slajd dla nowego slajdu. |
| allow_clone_missing_layout | **bool** | Jeśli w podanym masterze nie ma odpowiedniego layoutu, layout slajdu źródłowego zostanie sklonowany (gdy allowCloneMissingLayout jest prawdziwe) lub zostanie zgłoszony PptxEditException (gdy allowCloneMissingLayout jest fałszywe). |

### Wyjątki

| Wyjątek | Opis |
| :- | :- |
| [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception) | Zgłaszany, gdy w podanym masterze nie ma odpowiedniego layoutu i allowCloneMissingLayout jest fałszywe. |



### Zobacz także
* class [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* class [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide)
* class [`ISlide`](/slides/python-net/pl/aspose.slides/islide)
* class [`PptxEditException`](/slides/python-net/pl/aspose.slides/pptxeditexception)
* class [`SlideCollection`](/slides/python-net/pl/aspose.slides/slidecollection)
* module [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* library [`Aspose.Slides`](/slides/python-net)