---
title: ILayoutSlideCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een basis-klasse voor voor een verzameling van layout-slides.
type: docs
url: /nl/com.aspose.slides/ilayoutslidecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Stelt een basis-klasse voor voor een verzameling van layout-slides.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de layout-slide op index. |
| [getByType(byte type)](#getByType-byte-) | Retourneert de eerste layout-slide van het opgegeven type. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Verwijdert een layout uit de collectie. |
| [removeUnused()](#removeUnused--) | Verwijdert ongebruikte layout-slides (layout-slides waarvan HasDependingSlides false is). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Retourneert de layout-slide op index. Alleen-lezen [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int |  |

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


Retourneert de eerste layout-slide van het opgegeven type.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| type | byte | Een type van layout-slide om te vinden. |

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) met het opgegeven type of null als er geen layouts zijn gevonden.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Verwijdert een layout uit de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | De layout-slide die uit de collectie moet worden verwijderd.

--------------------

1) Om het werpen van de PptxEditException te voorkomen, controleer eerst de HasDependingSlides-eigenschap van de layout. 2) Je kunt ook de methode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) gebruiken om de code te vereenvoudigen. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Verwijdert ongebruikte layout-slides (layout-slides waarvan HasDependingSlides false is).