---
title: add_clone method
second_title: Aspose.Slides pro Python přes .NET referenci API
description: 
type: docs
url: /cs/aspose.slides/globallayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
Přidá kopii určeného rozvrhového snímku do prezentace.

### Vrácená hodnota

Přidaný snímek.

```python
def add_clone(self, source_layout):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Snímek ke klonování. |

### Poznámky

Při klonování rozvržení mezi různými prezentacemi může být také klonován master rozvržení, aby se zachovalo formátování zdroje.  
Interní registr je používán k sledování automaticky klonovaných masterů, aby se zabránilo vytvoření více kopií stejného master snímku.  
Manuální klonování master snímků nebude ani zabráněno, ani zaznamenáno.

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
Přidá kopii určeného rozvrhového snímku do prezentace.

### Vrácená hodnota

Přidaný snímek.

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| Parametr | Typ | Popis |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide) | Snímek ke klonování. |
| dest_master | [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide) | Master snímek pro nové rozvržení. |

### Poznámky

1) Nové rozvržení bude propojeno s definovaným masterem v cílové prezentaci.  
Jedná se o analogii kopírování/vkládání s volbou „Use Destination Theme“ v PowerPointu.  
2) Analogie této metody je metoda **Aspose.Slides.IMasterLayoutSlideCollection.AddClone(Aspose.Slide** přístupná přes vlastnost [`IMasterSlide.layout_slides`](/slides/python-net/cs/aspose.slides/imasterslide/layout_slides).

### Viz také
* třída [`GlobalLayoutSlideCollection`](/slides/python-net/cs/aspose.slides/globallayoutslidecollection)
* třída [`ILayoutSlide`](/slides/python-net/cs/aspose.slides/ilayoutslide)
* třída [`IMasterSlide`](/slides/python-net/cs/aspose.slides/imasterslide)
* modul [`aspose.slides`](/slides/python-net/cs/aspose.slides)
* knihovna [`Aspose.Slides`](/slides/python-net)