---
title: ILineFormat
second_title: Aspose.Slides voor Java API-referentie
description: Representeert het formaat van een lijn.
type: docs
url: /nl/com.aspose.slides/ilineformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Vertegenwoordigt het formaat van een lijn.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Geeft true terug als het lijnformaat niet is gedefinieerd (zoals net aangemaakt, standaard). |
| [getFillFormat()](#getFillFormat--) | Geeft het opvulformaat van een lijn terug. |
| [getSketchFormat()](#getSketchFormat--) | Geeft het schetsformaat van een lijn terug. |
| [getWidth()](#getWidth--) | Geeft of stelt de breedte van een lijn in. |
| [setWidth(double value)](#setWidth-double-) | Geeft of stelt de breedte van een lijn in. |
| [getDashStyle()](#getDashStyle--) | Geeft of stelt de dashstijl van een lijn in. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Geeft of stelt de dashstijl van een lijn in. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Geeft of stelt het aangepaste dash-patroon in. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Geeft of stelt het aangepaste dash-patroon in. |
| [getCapStyle()](#getCapStyle--) | Geeft of stelt de capstijl van een lijn in. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Geeft of stelt de capstijl van een lijn in. |
| [getStyle()](#getStyle--) | Geeft of stelt de lijnstijl in. |
| [setStyle(byte value)](#setStyle-byte-) | Geeft of stelt de lijnstijl in. |
| [getAlignment()](#getAlignment--) | Geeft of stelt de uitlijning van een lijn in. |
| [setAlignment(byte value)](#setAlignment-byte-) | Geeft of stelt de uitlijning van een lijn in. |
| [getJoinStyle()](#getJoinStyle--) | Geeft of stelt de verbindingsstijl van lijnen in. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Geeft of stelt de verbindingsstijl van lijnen in. |
| [getMiterLimit()](#getMiterLimit--) | Geeft of stelt de kniklimiet van een lijn in. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Geeft of stelt de kniklimiet van een lijn in. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Geeft of stelt de pijlkopstijl aan het begin van een lijn in. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Geeft of stelt de pijlkopstijl aan het begin van een lijn in. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Geeft of stelt de pijlkopstijl aan het einde van een lijn in. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Geeft of stelt de pijlkopstijl aan het einde van een lijn in. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Geeft of stelt de pijlkopbreedte aan het begin van een lijn in. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Geeft of stelt de pijlkopbreedte aan het begin van een lijn in. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Geeft of stelt de pijlkopbreedte aan het einde van een lijn in. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Geeft of stelt de pijlkopbreedte aan het einde van een lijn in. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Geeft of stelt de pijlkoplengte aan het begin van een lijn in. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Geeft of stelt de pijlkoplengte aan het begin van een lijn in. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Geeft of stelt de pijlkoplengte aan het einde van een lijn in. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Geeft of stelt de pijlkoplengte aan het einde van een lijn in. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Bepaalt of de twee LineFormat-instanties gelijk zijn. |
| [getEffective()](#getEffective--) | Haalt de effectieve lijnopmaakgegevens op met de toegepaste overerving. |

### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Geeft true terug als het lijnformaat niet is gedefinieerd (zoals net aangemaakt, standaard). Alleen-lezen boolean.

**Retour:**
boolean

### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Geeft het opvulformaat van een lijn terug. Alleen-lezen [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Retour:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)

### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Geeft het schetsformaat van een lijn terug. Alleen-lezen [ISketchFormat](../../com.aspose.slides/isketchformat).

**Retour:**
[ISketchFormat](../../com.aspose.slides/isketchformat)

### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Geeft of stelt de breedte van een lijn in. Lezen/schrijven double.

**Retour:**
double

### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Geeft of stelt de breedte van een lijn in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Geeft of stelt de dashstijl van een lijn in. Lezen/schrijven [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Retour:**
byte

### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Geeft of stelt de dashstijl van een lijn in. Lezen/schrijven [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Geeft of stelt het aangepaste dash-patroon in. Lezen/schrijven float[].

**Retour:**
float[]

### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Geeft of stelt het aangepaste dash-patroon in. Lezen/schrijven float[].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float[] |  |

### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Geeft of stelt de capstijl van een lijn in. Lezen/schrijven [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Retour:**
byte

### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Geeft of stelt de capstijl van een lijn in. Lezen/schrijven [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Geeft of stelt de lijnstijl in. Lezen/schrijven [LineStyle](../../com.aspose.slides/linestyle).

**Retour:**
byte

### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Geeft of stelt de lijnstijl in. Lezen/schrijven [LineStyle](../../com.aspose.slides/linestyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Geeft of stelt de uitlijning van een lijn in. Lezen/schrijven [LineAlignment](../../com.aspose.slides/linealignment).

**Retour:**
byte

### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Geeft of stelt de uitlijning van een lijn in. Lezen/schrijven [LineAlignment](../../com.aspose.slides/linealignment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Geeft of stelt de verbindingsstijl van lijnen in. Lezen/schrijven [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Retour:**
byte

### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Geeft of stelt de verbindingsstijl van lijnen in. Lezen/schrijven [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Geeft of stelt de kniklimiet van een lijn in. Lezen/schrijven float.

**Retour:**
float

### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Geeft of stelt de kniklimiet van een lijn in. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Geeft of stelt de pijlkopstijl aan het begin van een lijn in. Lezen/schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retour:**
byte

### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Geeft of stelt de pijlkopstijl aan het begin van een lijn in. Lezen/schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Geeft of stelt de pijlkopstijl aan het einde van een lijn in. Lezen/schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retour:**
byte

### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Geeft of stelt de pijlkopstijl aan het einde van een lijn in. Lezen/schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Geeft of stelt de pijlkopbreedte aan het begin van een lijn in. Lezen/schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retour:**
byte

### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Geeft of stelt de pijlkopbreedte aan het begin van een lijn in. Lezen/schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Geeft of stelt de pijlkopbreedte aan het einde van een lijn in. Lezen/schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retour:**
byte

### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Geeft of stelt de pijlkopbreedte aan het einde van een lijn in. Lezen/schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Geeft of stelt de pijlkoplengte aan het begin van een lijn in. Lezen/schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retour:**
byte

### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Geeft of stelt de pijlkoplengte aan het begin van een lijn in. Lezen/schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Geeft of stelt de pijlkoplengte aan het einde van een lijn in. Lezen/schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retour:**
byte

### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public abstract void setEndArrowheadLength(byte value)
```

Geeft of stelt de pijlkoplengte aan het einde van een lijn in. Lezen/schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public abstract boolean equals(ILineFormat lineFormat)
```

Bepaalt of de twee LineFormat-instanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | De LineFormat om te vergelijken met de huidige LineFormat. |

**Retour:**
boolean - **true** als de opgegeven LineFormat gelijk is aan de huidige LineFormat; anders **false**.

### getEffective() {#getEffective--}
```
public abstract ILineFormatEffectiveData getEffective()
```

Haalt de effectieve lijnopmaakgegevens op met de toegepaste overerving.

**Retour:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - Een [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).