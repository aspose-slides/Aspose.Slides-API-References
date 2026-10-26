---
title: SlideSize
second_title: Aspose.Slides för Java API-referens
description: Representerar storlek och orientering för en bild.
type: docs
url: /sv/com.aspose.slides/slidesize/
---
**Arv:**
java.lang.Object, com.aspose.slides.DomObject

**Alla implementerade gränssnitt:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Representerar storlek och orientering för en bild.
## Metoder

| Method | Description |
| --- | --- |
| [getSize()](#getSize--) | Hämtar bildens dimensioner i punkter. |
| [getType()](#getType--) | Hämtar bildens storlekstyp. |
| [getOrientation()](#getOrientation--) | Hämtar eller anger bildens orientering. |
| [setOrientation(int value)](#setOrientation-int-) | Hämtar eller anger bildens orientering. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Ställer in bildstorleken efter typ och skalar befintligt innehåll. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Ställer in bildens dimensioner explicit och skalar befintligt innehåll. |
### getSize() {#getSize--}
```
public final Dimension2D getSize()
```

Hämtar bildens dimensioner i punkter.

--------------------

Att tilldela ett nytt värde återställer egenskapen #getType.getType till [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) och sätter #getOrientation.getOrientation/#setOrientation(int).setOrientation(int).

**Returnerar:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public final int getType()
```

Hämtar bildens storlekstyp.

--------------------

Att tilldela något annat värde än [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) justerar #getSize.getSize enligt de fördefinierade dimensionerna, samtidigt som den aktuella #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) behålls.

**Returnerar:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```

Hämtar eller anger bildens orientering.

--------------------

Att ändra detta värde byter bildens bredd och höjd.

**Returnerar:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```

Hämtar eller anger bildens orientering.

--------------------

Att ändra detta värde byter bildens bredd och höjd.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

Ställer in bildstorleken efter typ och skalar befintligt innehåll.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| type | int | Den fördefinierade bildstorleken att tillämpa. |
| scaleType | int | Skalningsläge för innehållet som ska användas. |

--------------------

Att tilldela något annat värde än [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) justerar #getSize.getSize baserat på den valda typen, samtidigt som #getOrientation.getOrientation/#setOrientation(int).setOrientation(int) bevaras. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Ställer in bildens dimensioner explicit och skalar befintligt innehåll.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| width | float | Den nya bildbredden i punkter. |
| height | float | Den nya bildhöjden i punkter. |
| scaleType | int | Skalningsläge för innehållet som ska användas. |

--------------------

Detta återställer egenskapen #getType.getType till [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) och sätter #getOrientation.getOrientation/#setOrientation(int).setOrientation(int). |