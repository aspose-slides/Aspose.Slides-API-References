---
title: add_clone method
second_title: Aspose.Slides dla Pythona – referencja API .NET
description: 
type: docs
url: /pl/aspose.slides/globallayoutslidecollection/add_clone/
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

Podczas klonowania układu między różnymi prezentacjami master układu może zostać również sklonowany, aby zachować formatowanie źródła.  
Rejestr wewnętrzny jest używany do śledzenia automatycznie sklonowanych masterów w celu zapobieżenia tworzeniu wielu klonów tego samego slajdu master.  
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

1) Nowy układ zostanie powiązany z określonym masterem w docelowej prezentacji.  
   Jest to odpowiednik kopiuj/wklej z opcją „Użyj tematu docelowego” w PowerPoint.  
2) Odpowiednikiem tej metody jest metoda **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** dostępna poprzez właściwość [`IMasterSlide.layout_slides`](/slides/python-net/pl/aspose.slides/imasterslide/layout_slides).



### Zobacz także
* klasa [`GlobalLayoutSlideCollection`](/slides/python-net/pl/aspose.slides/globallayoutslidecollection)
* klasa [`ILayoutSlide`](/slides/python-net/pl/aspose.slides/ilayoutslide)
* klasa [`IMasterSlide`](/slides/python-net/pl/aspose.slides/imasterslide)
* moduł [`aspose.slides`](/slides/python-net/pl/aspose.slides)
* biblioteka [`Aspose.Slides`](/slides/python-net)