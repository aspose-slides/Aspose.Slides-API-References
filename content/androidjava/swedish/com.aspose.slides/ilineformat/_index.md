---
title: ILineFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar formatet för en linje.
type: docs
url: /sv/com.aspose.slides/ilineformat/
---
**Alla implementerade gränssnitt:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Representerar formatet för en linje.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Returnerar true om linjeformatet inte är definierat (som precis skapad, standard). |
| [getFillFormat()](#getFillFormat--) | Returnerar fyllningsformatet för en linje. |
| [getSketchFormat()](#getSketchFormat--) | Returnerar skissformatet för en linje. |
| [getWidth()](#getWidth--) | Returnerar eller anger bredden på en linje. |
| [setWidth(double value)](#setWidth-double-) | Returnerar eller anger bredden på en linje. |
| [getDashStyle()](#getDashStyle--) | Returnerar eller anger linjens streckstil. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Returnerar eller anger linjens streckstil. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Returnerar eller anger det anpassade streckmönstret. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Returnerar eller anger det anpassade streckmönstret. |
| [getCapStyle()](#getCapStyle--) | Returnerar eller anger linjens ändstil. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Returnerar eller anger linjens ändstil. |
| [getStyle()](#getStyle--) | Returnerar eller anger linjens stil. |
| [setStyle(byte value)](#setStyle-byte-) | Returnerar eller anger linjens stil. |
| [getAlignment()](#getAlignment--) | Returnerar eller anger linjens justering. |
| [setAlignment(byte value)](#setAlignment-byte-) | Returnerar eller anger linjens justering. |
| [getJoinStyle()](#getJoinStyle--) | Returnerar eller anger fogstilen för linjer. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Returnerar eller anger fogstilen för linjer. |
| [getMiterLimit()](#getMiterLimit--) | Returnerar eller anger snittgränsen för en linje. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Returnerar eller anger snittgränsen för en linje. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Returnerar eller anger pilspetsens stil i början av en linje. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Returnerar eller anger pilspetsens stil i början av en linje. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Returnerar eller anger pilspetsens stil i slutet av en linje. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Returnerar eller anger pilspetsens stil i slutet av en linje. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Returnerar eller anger pilspetsens bredd i början av en linje. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Returnerar eller anger pilspetsens bredd i början av en linje. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Returnerar eller anger pilspetsens bredd i slutet av en linje. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Returnerar eller anger pilspetsens bredd i slutet av en linje. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Returnerar eller anger pilspetsens längd i början av en linje. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Returnerar eller anger pilspetsens längd i början av en linje. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Returnerar eller anger pilspetsens längd i slutet av en linje. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Returnerar eller anger pilspetsens längd i slutet av en linje. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Fastställer om de två LineFormat-instanserna är lika. |
| [getEffective()](#getEffective--) | Hämtar effektiv linjeformateringsdata med arv tillämpat. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Returnerar true om linjeformatet inte är definierat (som precis skapad, standard). Skrivskyddad boolean.

**Returnerar:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Returnerar fyllningsformatet för en linje. Skrivskyddad [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Returnerar:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Returnerar skissformatet för en linje. Skrivskyddad [ISketchFormat](../../com.aspose.slides/isketchformat).

**Returnerar:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Returnerar eller anger bredden på en linje. Läs/skriv double.

**Returnerar:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Returnerar eller anger bredden på en linje. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Returnerar eller anger linjens streckstil. Läs/skriv [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Returnerar:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Returnerar eller anger linjens streckstil. Läs/skriv [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Returnerar eller anger det anpassade streckmönstret. Läs/skriv float[].

**Returnerar:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Returnerar eller anger det anpassade streckmönstret. Läs/skriv float[].

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Returnerar eller anger linjens ändstil. Läs/skriv [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Returnerar:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Returnerar eller anger linjens ändstil. Läs/skriv [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Returnerar eller anger linjens stil. Läs/skriv [LineStyle](../../com.aspose.slides/linestyle).

**Returnerar:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Returnerar eller anger linjens stil. Läs/skriv [LineStyle](../../com.aspose.slides/linestyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Returnerar eller anger linjens justering. Läs/skriv [LineAlignment](../../com.aspose.slides/linealignment).

**Returnerar:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Returnerar eller anger linjens justering. Läs/skriv [LineAlignment](../../com.aspose.slides/linealignment).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Returnerar eller anger fogstilen för linjer. Läs/skriv [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Returnerar:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Returnerar eller anger fogstilen för linjer. Läs/skriv [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Returnerar eller anger snittgränsen för en linje. Läs/skriv float.

**Returnerar:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Returnerar eller anger snittgränsen för en linje. Läs/skriv float.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Returnerar eller anger pilspetsens stil i början av en linje. Läs/skriv [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returnerar:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Returnerar eller anger pilspetsens stil i början av en linje. Läs/skriv [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Returnerar eller anger pilspetsens stil i slutet av en linje. Läs/skriv [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Returnerar:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Returnerar eller anger pilspetsens stil i slutet av en linje. Läs/skriv [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Returnerar eller anger pilspetsens bredd i början av en linje. Läs/skriv [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returnerar:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Returnerar eller anger pilspetsens bredd i början av en linje. Läs/skriv [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Returnerar eller anger pilspetsens bredd i slutet av en linje. Läs/skriv [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Returnerar:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Returnerar eller anger pilspetsens bredd i slutet av en linje. Läs/skriv [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Returnerar eller anger pilspetsens längd i början av en linje. Läs/skriv [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returnerar:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Returnerar eller anger pilspetsens längd i början av en linje. Läs/skriv [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Returnerar eller anger pilspetsens längd i slutet av en linje. Läs/skriv [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Returnerar:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Returnerar eller anger pilspetsens längd i slutet av en linje. Läs/skriv [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Fastställer om de två LineFormat-instanserna är lika.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | Den LineFormat som ska jämföras med den aktuella LineFormat. |

**Returnerar:**
boolean - **true** om den angivna LineFormat är lika med den aktuella LineFormat; annars **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Hämtar effektiv linjeformateringsdata med arv tillämpat.

**Returnerar:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - En [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).