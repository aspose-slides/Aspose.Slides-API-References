---
title: SlideSize
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar storleken och orienteringen av en bild.
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

Representerar storleken och orienteringen av en bild.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getSize()](#getSize--) | Hämtar bildens dimensioner i punkter. |
| [getType()](#getType--) | Hämtar bildens storlekstyp. |
| [getOrientation()](#getOrientation--) | Hämtar eller anger bildens orientering. |
| [setOrientation(int value)](#setOrientation-int-) | Hämtar eller anger bildens orientering. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Ställer in bildens storlek efter typ och skalar befintligt innehåll. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Ställer in bildens dimensioner explicit och skalar befintligt innehåll. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```

Hämtar bildens dimensioner i punkter.

--------------------

Tilldelning av ett nytt värde återställer egenskapen \#getType.getType till [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) och sätter \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Returnerar:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```

Hämtar bildens storlekstyp.

--------------------

Tilldelning av ett värde annat än [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) justerar \#getSize.getSize enligt de fördefinierade dimensionerna, samtidigt som den nuvarande \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) behålls.

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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```

Ställer in bildens storlek efter typ och skalar befintligt innehåll.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| type | int | Den fördefinierade bildstorlek som ska tillämpas. |
| scaleType | int | Det skalningsläge för innehållet som ska användas. |

--------------------

Tilldelning av ett värde annat än [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) justerar \#getSize.getSize baserat på den valda typen, samtidigt som \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int) bevaras. |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```

Ställer in bildens dimensioner explicit och skalar befintligt innehåll.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| width | float | Den nya bildbredden i punkter. |
| height | float | Den nya bildhöjden i punkter. |
| scaleType | int | Det skalningsläge för innehållet som ska användas. |

--------------------

Detta återställer egenskapen \#getType.getType till [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) och sätter \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).