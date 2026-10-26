---
title: add_clone method
second_title: Aspose.Slides pro Python pomocí .NET API Reference
description: 
type: docs
url: /cs/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Přidá kopii určeného rozložení snímku do prezentace.

### Returns

Přidaný snímek.



```python
def add_clone(self, source_layout):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Snímek ke klonování. |

### Remarks

Při klonování layoutu mezi různými prezentacemi může být také klonován master layoutu, aby se zachovalo formátování zdroje. Interní registr se používá k sledování automaticky klonovaných masterů, aby se zabránilo vytvoření více kopií stejného master snímku. Ruční klonování master snímků nebude ani zamezeno, ani registrováno.


## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Přidá kopii určeného rozložení snímku do prezentace.

### Returns

Přidaný snímek.



```python
def add_clone(self, source_layout, dest_master):
    ...
```


| Parametr | Typ | Popis |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Snímek ke klonování. |
| dest_master | [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide) | Master snímek pro nové rozložení. |

### Remarks

Nové rozložení bude propojeno s definovaným masterem v cílové prezentaci. Takže je to ekvivalent kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu.



### See Also
* třída [`IGlobalLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/igloballayoutslidecollection)
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)