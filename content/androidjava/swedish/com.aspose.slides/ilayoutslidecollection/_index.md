---
title: ILayoutSlideCollection
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar en basklass för en samling av layoutbilder.
type: docs
url: /sv/com.aspose.slides/ilayoutslidecollection/
---
**Alla implementerade gränssnitt:**
com.aspose.slides.IGenericCollection
```
public interface ILayoutSlideCollection extends IGenericCollection<ILayoutSlide>
```

Representerar en basklass för en samling av layoutbilder.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Returnerar layoutbilden efter index. |
| [getByType(byte type)](#getByType-byte-) | Returnerar den första layoutbilden av angiven typ. |
| [remove(ILayoutSlide value)](#remove-com.aspose.slides.ILayoutSlide-) | Tar bort en layout från samlingen. |
| [removeUnused()](#removeUnused--) | Tar bort oanvända layoutbilder (layoutbilder vars HasDependingSlides är falskt). |
### get_Item(int index) {#get-Item-int-}
```
public abstract ILayoutSlide get_Item(int index)
```


Returnerar layoutbilden efter index. Skrivskyddad [ILayoutSlide](../../com.aspose.slides/ilayoutslide).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | int |  |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide)
### getByType(byte type) {#getByType-byte-}
```
public abstract ILayoutSlide getByType(byte type)
```


Returnerar den första layoutbilden av angiven typ.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | byte | En typ av layoutbild att hitta. |

**Returnerar:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - [ILayoutSlide](../../com.aspose.slides/ilayoutslide) med angiven typ eller null om inga layouter hittades.
### remove(ILayoutSlide value) {#remove-com.aspose.slides.ILayoutSlide-}
```
public abstract void remove(ILayoutSlide value)
```


Tar bort en layout från samlingen.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Layoutbilden som ska tas bort från samlingen.

--------------------

1) För att undvika att ett PptxEditException kastas, kontrollera layoutens HasDependingSlides-egendom först. 2) Du kan också använda [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove)-metoden för att förenkla koden. |
### removeUnused() {#removeUnused--}
```
public abstract void removeUnused()
```


Tar bort oanvända layoutbilder (layoutbilder vars HasDependingSlides är falskt).