---
title: add_clone method
second_title: Aspose.Slides dla Pythona przez .NET Referencja API
description: 
type: docs
url: /pl/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Dodaje kopię określonego slajdu układu do prezentacji.

### Zwraca

Dodany slajd.



```python
def add_clone(self, source_layout):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Slajd do sklonowania. |

### Uwagi

Podczas klonowania układu między różnymi prezentacjami master układu może zostać również sklonowany
            aby zachować formatowanie źródła.
            Rejestr wewnętrzny jest używany do śledzenia automatycznie sklonowanych masterów, aby zapobiec tworzeniu 
            wielokrotnych klonów tego samego slajdu master.
            Ręczne klonowanie slajdów master nie będzie ani zapobiegane, ani rejestrowane.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Dodaje kopię określonego slajdu układu do prezentacji.

### Zwraca

Dodany slajd.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parametr | Typ | Opis |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide) | Slajd do sklonowania. |
| dest_master | [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide) | Slajd master dla nowego układu. |

### Uwagi

Nowy układ zostanie powiązany z określonym masterem w docelowej prezentacji.
            Jest to analogia do kopiuj/wklej z opcją "Use Destination Theme" w PowerPoint.



### Zobacz także
* klasa [`IGlobalLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/igloballayoutslidecollection)
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)