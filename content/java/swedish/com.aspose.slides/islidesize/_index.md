---
title: ISlideSize
second_title: Aspose.Slides for Java API Reference
description: Representerar storleken och orienteringen av en bild.
type: docs
url: /sv/com.aspose.slides/islidesize/
---```
public interface ISlideSize
```

Representerar storleken och orienteringen av en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSize()](#getSize--) | Hämtar bildens dimensioner i punkter. |
| [getType()](#getType--) | Hämtar bildens storlekstyp. |
| [getOrientation()](#getOrientation--) | Hämtar eller anger bildens orientering. |
| [setOrientation(int value)](#setOrientation-int-) | Hämtar eller anger bildens orientering. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Anger bildens storlek efter typ och skalar befintligt innehåll. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Anger bildens dimensioner explicit och skalar befintligt innehåll. |
### getSize() {#getSize--}
```
public abstract Dimension2D getSize()
```

Hämtar bildens dimensioner i punkter.

--------------------

Att tilldela ett nytt värde återställer egenskapen \#getType.getType till [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) och sätter \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Returnerar:**
java.awt.geom.Dimension2D
### getType() {#getType--}
```
public abstract int getType()
```

Hämtar bildens storlekstyp.

--------------------

Att tilldela något värde annat än [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) justerar \#getSize.getSize enligt de fördefinierade dimensionerna, samtidigt som den nuvarande \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) behålls.

**Returnerar:**
int
### getOrientation() {#getOrientation--}
```
public abstract int getOrientation()
```

Hämtar eller anger bildens orientering.

--------------------

Att ändra detta värde byter bildens bredd och höjd.

**Returnerar:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public abstract void setOrientation(int value)
```

Hämtar eller anger bildens orientering.

--------------------

Att ändra detta värde byter bildens bredd och höjd.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public abstract void setSize(int type, int scaleType)
```

Anger bildens storlek efter typ och skalar befintligt innehåll.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Den fördefinierade bildstorleken att tillämpa. |
| scaleType | int | Skalningsläget för innehållet att använda. |

--------------------

Att tilldela något värde annat än [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) justerar \#getSize.getSize baserat på den valda typen, samtidigt som \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) bevaras. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public abstract void setSize(float width, float height, int scaleType)
```

Anger bildens dimensioner explicit och skalar befintligt innehåll.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | float | Den nya bildbredden, i punkter. |
| height | float | Den nya bildhöjden, i punkter. |
| scaleType | int | Skalningsläget för innehållet att använda. |

--------------------

Detta återställer egenskapen \#getType.getType till [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) och sätter {\#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |