---
title: LineFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar formatet för en linje.
type: docs
url: /sv/com.aspose.slides/lineformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Representerar formatet för en linje.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Returnerar true om linjeformatet inte är definierat (såsom precis skapad, standard). |
| [getFillFormat()](#getFillFormat--) | Returnerar fyllningsformatet för en linje. |
| [getSketchFormat()](#getSketchFormat--) | Returnerar skissformatet för en linje. |
| [getWidth()](#getWidth--) | Returnerar eller sätter bredden på en linje. |
| [setWidth(double value)](#setWidth-double-) | Returnerar eller sätter bredden på en linje. |
| [getDashStyle()](#getDashStyle--) | Returnerar eller sätter streckstilen för linjen. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Returnerar eller sätter streckstilen för linjen. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returnerar eller sätter anpassat streckmönster. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Returnerar eller sätter anpassat streckmönster. |
| [getCapStyle()](#getCapStyle--) | Returnerar eller sätter linjens cap-stil. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Returnerar eller sätter linjens cap-stil. |
| [getStyle()](#getStyle--) | Returnerar eller sätter linjestilen. |
| [setStyle(byte value)](#setStyle-byte-) | Returnerar eller sätter linjestilen. |
| [getAlignment()](#getAlignment--) | Returnerar eller sätter linjens justering. |
| [setAlignment(byte value)](#setAlignment-byte-) | Returnerar eller sätter linjens justering. |
| [getJoinStyle()](#getJoinStyle--) | Returnerar eller sätter join-stilen för linjer. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Returnerar eller sätter join-stilen för linjer. |
| [getMiterLimit()](#getMiterLimit--) | Returnerar eller sätter miter-gränsen för en linje. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Returnerar eller sätter miter-gränsen för en linje. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returnerar eller sätter pilhuvudstilen i början av en linje. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Returnerar eller sätter pilhuvudstilen i början av en linje. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returnerar eller sätter pilhuvudstilen i slutet av en linje. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Returnerar eller sätter pilhuvudstilen i slutet av en linje. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returnerar eller sätter bredden på pilhuvudet i början av en linje. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Returnerar eller sätter bredden på pilhuvudet i början av en linje. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returnerar eller sätter bredden på pilhuvudet i slutet av en linje. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Returnerar eller sätter bredden på pilhuvudet i slutet av en linje. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returnerar eller sätter längden på pilhuvudet i början av en linje. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Returnerar eller sätter längden på pilhuvudet i början av en linje. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returnerar eller sätter längden på pilhuvudet i slutet av en linje. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Returnerar eller sätter längden på pilhuvudet i slutet av en linje. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Bestämmer om de två LineFormat-instanserna är lika. |
| [getEffective()](#getEffective--) | Hämtar effektiv linjeformateringsdata med arv tillämpat. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Version. Skrivskyddad long.

**Returnerar:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Jämför med specificerat objekt.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Returnerar:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```


Returnerar true om linjeformatet inte är definierat (såsom precis skapad, standard). Skrivskyddad boolean .

**Returnerar:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```


Returnerar fyllningsformatet för en linje. Skrivskyddad [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Returnerar:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```


Returnerar skissformatet för en linje. Skrivskyddad [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Returnerar:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Returnerar eller sätter bredden på en linje. Läs/skriv double .

**Returnerar:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Returnerar eller sätter bredden på en linje. Läs/skriv double .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```


Returnerar eller sätter streckstilen för linjen. Läs/skriv [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Returnerar:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```


Returnerar eller sätter streckstilen för linjen. Läs/skriv [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```


Returnerar eller sätter anpassat streckmönster. Läs/skriv float[] .

**Returnerar:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```


Returnerar eller sätter anpassat streckmönster. Läs/skriv float[] .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```


Returnerar eller sätter linjens cap-stil. Läs/skriv [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Returnerar:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```


Returnerar eller sätter linjens cap-stil. Läs/skriv [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```


Returnerar eller sätter linjestilen. Läs/skriv [LineStyle](../../com.aspose.slides/linestyle).

**Returnerar:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```


Returnerar eller sätter linjestilen. Läs/skriv [LineStyle](../../com.aspose.slides/linestyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```


Returnerar eller sätter linjens justering. Läs/skriv [LineAlignment](../../com.aspose.slides/linealignment).

**Returnerar:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```


Returnerar eller sätter linjens justering. Läs/skriv [LineAlignment](../../com.aspose.slides/linealignment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```


Returnerar eller sätter join-stilen för linjer. Läs/skriv [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Returnerar:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```


Returnerar eller sätter join-stilen för linjer. Läs/skriv [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Returnerar eller sätter miter-gränsen för en linje. Läs/skriv float .

**Returnerar:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Returnerar eller sätter miter-gränsen för en linje. Läs/skriv float .

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```


Returnerar eller sätter pilhuvudstilen i början av en linje. Läs/skriv [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returnerar:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```


Returnerar eller sätter pilhuvudstilen i början av en linje. Läs/skriv [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```


Returnerar eller sätter pilhuvudstilen i slutet av en linje. Läs/skriv [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returnerar:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```


Returnerar eller sätter pilhuvudstilen i slutet av en linje. Läs/skriv [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```


Returnerar eller sätter bredden på pilhuvudet i början av en linje. Läs/skriv [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returnerar:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```


Returnerar eller sätter bredden på pilhuvudet i början av en linje. Läs/skriv [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```


Returnerar eller sätter bredden på pilhuvudet i slutet av en linje. Läs/skriv [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returnerar:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```


Returnerar eller sätter bredden på pilhuvudet i slutet av en linje. Läs/skriv [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```


Returnerar eller sätter längden på pilhuvudet i början av en linje. Läs/skriv [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returnerar:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```


Returnerar eller sätter längden på pilhuvudet i början av en linje. Läs/skriv [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```


Returnerar eller sätter längden på pilhuvudet i slutet av en linje. Läs/skriv [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returnerar:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```


Returnerar eller sätter längden på pilhuvudet i slutet av en linje. Läs/skriv [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```


Bestämmer om de två LineFormat-instanserna är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | LineFormat att jämföra med det aktuella LineFormat. |

**Returnerar:**
boolean – **true** om den specificerade LineFormat är lika med den aktuella LineFormat; annars **false**.
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```


Hämtar effektiv linjeformateringsdata med arv tillämpat.

--------------------

> ```
> This example demonstrates getting shape's effective line format properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>  	ILineFormatEffectiveData effectiveLineFormat = pres.getSlides().get_Item(0).getShapes().get_Item(0).getLineFormat().getEffective();
>  	System.out.println("Style: " + effectiveLineFormat.getStyle());
>  	System.out.println("Width: " + effectiveLineFormat.getWidth());
>  	System.out.println("Fill type: " + effectiveLineFormat.getFillFormat().getFillType());
>  } finally {
>   if (pres != null) pres.dispose();
>  }
> ```

**Returnerar:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - En [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).