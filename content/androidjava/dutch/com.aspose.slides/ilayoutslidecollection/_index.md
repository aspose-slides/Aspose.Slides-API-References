---
title: ILayoutSlideCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een basisklasse voor voor een collectie van lay-outdia's.
type: docs
url: /nl/com.aspose.slides/ilayoutslidecollection/
---
**Alle geïmplementeerde interfaces:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Stelt een basisklasse voor voor een collectie van lay-outdia's.
## Methods

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retourneert de lay-outdia op basis van de index. |
| [getByType(byte type)](#getByType-byte-) | Retourneert de eerste lay-outdia van het opgegeven type. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Verwijdert een lay-out uit de collectie. |
| [removeUnused()](#removeUnused--) | Verwijdert ongebruikte lay-outdia's (lay-outdia's waarvan HasDependingSlides false is). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Retourneert de lay-outdia op basis van de index. Alleen-lezen [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


Retourneert de eerste lay-outdia van het opgegeven type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | byte | Een type van lay-outdia om te vinden. |

**Returns:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) met opgegeven type of null als er geen lay-outs gevonden zijn.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Verwijdert een lay-out uit de collectie.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | De lay-outdia die uit de collectie moet worden verwijderd.

--------------------

1) Om het gooien van de PptxEditException te voorkomen, controleer eerst de HasDependingSlides-eigenschap van de lay-out. 2) Je kunt ook de [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove)-methode gebruiken om de code te vereenvoudigen. |

### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Verwijdert ongebruikte lay-outdia's (lay-outdia's waarvan HasDependingSlides false is).