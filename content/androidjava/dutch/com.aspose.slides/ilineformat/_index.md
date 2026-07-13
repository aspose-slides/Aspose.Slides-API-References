---
title: ILineFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt het formaat van een lijn voor.
type: docs
url: /nl/com.aspose.slides/ilineformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILineParamSource](../../com.aspose.slides/ilineparamsource)
```
public interface ILineFormat extends ILineParamSource
```

Stelt het formaat van een lijn voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isFormatNotDefined()](#isFormatNotDefined--) | Retourneert true als het lijnformaat niet is gedefinieerd (net aangemaakt, standaard). |
| [getFillFormat()](#getFillFormat--) | Retourneert het opvulformaat van een lijn. |
| [getSketchFormat()](#getSketchFormat--) | Retourneert het schetsformaat van een lijn. |
| [getWidth()](#getWidth--) | Retourneert of stelt de breedte van een lijn in. |
| [setWidth(double value)](#setWidth-double-) | Retourneert of stelt de breedte van een lijn in. |
| [getDashStyle()](#getDashStyle--) | Retourneert of stelt de streepstijl van de lijn in. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Retourneert of stelt de streepstijl van de lijn in. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Retourneert of stelt het aangepaste streeppatroon in. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Retourneert of stelt het aangepaste streeppatroon in. |
| [getCapStyle()](#getCapStyle--) | Retourneert of stelt de capstijl van de lijn in. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Retourneert of stelt de capstijl van de lijn in. |
| [getStyle()](#getStyle--) | Retourneert of stelt de lijnstijl in. |
| [setStyle(byte value)](#setStyle-byte-) | Retourneert of stelt de lijnstijl in. |
| [getAlignment()](#getAlignment--) | Retourneert of stelt de lijnuitlijning in. |
| [setAlignment(byte value)](#setAlignment-byte-) | Retourneert of stelt de lijnuitlijning in. |
| [getJoinStyle()](#getJoinStyle--) | Retourneert of stelt de samengevoegde stijl van de lijnen in. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Retourneert of stelt de samengevoegde stijl van de lijnen in. |
| [getMiterLimit()](#getMiterLimit--) | Retourneert of stelt de schuine limiet van een lijn in. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Retourneert of stelt de schuine limiet van een lijn in. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Retourneert of stelt de pijlpuntstijl aan het begin van een lijn in. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Retourneert of stelt de pijlpuntstijl aan het begin van een lijn in. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Retourneert of stelt de pijlpuntstijl aan het einde van een lijn in. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Retourneert of stelt de pijlpuntstijl aan het einde van een lijn in. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Retourneert of stelt de pijlpuntbreedte aan het begin van een lijn in. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Retourneert of stelt de pijlpuntbreedte aan het begin van een lijn in. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Retourneert of stelt de pijlpuntbreedte aan het einde van een lijn in. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Retourneert of stelt de pijlpuntbreedte aan het einde van een lijn in. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Retourneert of stelt de pijlpuntlengte aan het begin van een lijn in. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Retourneert of stelt de pijlpuntlengte aan het begin van een lijn in. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Retourneert of stelt de pijlpuntlengte aan het einde van een lijn in. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Retourneert of stelt de pijlpuntlengte aan het einde van een lijn in. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Bepaalt of de twee LineFormat-instanties gelijk zijn. |
| [getEffective()](#getEffective--) | Haalt de effectieve lijnopmaakgegevens op met de toegepaste overerving. |
### isFormatNotDefined() {#isFormatNotDefined--}
```
public abstract boolean isFormatNotDefined()
```

Retourneert true als het lijnformaat niet is gedefinieerd (net aangemaakt, standaard). Alleen-lezen boolean.

**Retour:**
boolean
### getFillFormat() {#getFillFormat--}
```
public abstract ILineFillFormat getFillFormat()
```

Retourneert het opvulformaat van een lijn. Alleen-lezen [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Retour:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public abstract ISketchFormat getSketchFormat()
```

Retourneert het schetsformaat van een lijn. Alleen-lezen [ISketchFormat](../../com.aspose.slides/isketchformat).

**Retour:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public abstract double getWidth()
```

Retourneert of stelt de breedte van een lijn in. Lezen/schrijven double.

**Retour:**
double
### setWidth(double value) {#setWidth-double-}
```
public abstract void setWidth(double value)
```

Retourneert of stelt de breedte van een lijn in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public abstract byte getDashStyle()
```

Retourneert of stelt de streepstijl van de lijn in. Lezen/schrijven [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Retour:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public abstract void setDashStyle(byte value)
```

Retourneert of stelt de streepstijl van de lijn in. Lezen/schrijven [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public abstract float[] getCustomDashPattern()
```

Retourneert of stelt het aangepaste streeppatroon in. Lezen/schrijven float[].

**Retour:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public abstract void setCustomDashPattern(float[] value)
```

Retourneert of stelt het aangepaste streeppatroon in. Lezen/schrijven float[].

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public abstract byte getCapStyle()
```

Retourneert of stelt de capstijl van de lijn in. Lezen/schrijven [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Retour:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public abstract void setCapStyle(byte value)
```

Retourneert of stelt de capstijl van de lijn in. Lezen/schrijven [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public abstract byte getStyle()
```

Retourneert of stelt de lijnstijl in. Lezen/schrijven [LineStyle](../../com.aspose.slides/linestyle).

**Retour:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public abstract void setStyle(byte value)
```

Retourneert of stelt de lijnstijl in. Lezen/schrijven [LineStyle](../../com.aspose.slides/linestyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public abstract byte getAlignment()
```

Retourneert of stelt de lijnuitlijning in. Lezen/schrijven [LineAlignment](../../com.aspose.slides/linealignment).

**Retour:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public abstract void setAlignment(byte value)
```

Retourneert of stelt de lijnuitlijning in. Lezen/schrijven [LineAlignment](../../com.aspose.slides/linealignment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public abstract byte getJoinStyle()
```

Retourneert of stelt de samengevoegde stijl van de lijnen in. Lezen/schrijven [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Retour:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public abstract void setJoinStyle(byte value)
```

Retourneert of stelt de samengevoegde stijl van de lijnen in. Lezen/schrijven [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public abstract float getMiterLimit()
```

Retourneert of stelt de schuine limiet van een lijn in. Lezen/schrijven float.

**Retour:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public abstract void setMiterLimit(float value)
```

Retourneert of stelt de schuine limiet van een lijn in. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public abstract byte getBeginArrowheadStyle()
```

Retourneert of stelt de pijlpuntstijl aan het begin van een lijn in. Lezen/schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retour:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public abstract void setBeginArrowheadStyle(byte value)
```

Retourneert of stelt de pijlpuntstijl aan het begin van een lijn in. Lezen/schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public abstract byte getEndArrowheadStyle()
```

Retourneert of stelt de pijlpuntstijl aan het einde van een lijn in. Lezen/schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retour:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public abstract void setEndArrowheadStyle(byte value)
```

Retourneert of stelt de pijlpuntstijl aan het einde van een lijn in. Lezen/schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public abstract byte getBeginArrowheadWidth()
```

Retourneert of stelt de pijlpuntbreedte aan het begin van een lijn in. Lezen/schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retour:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public abstract void setBeginArrowheadWidth(byte value)
```

Retourneert of stelt de pijlpuntbreedte aan het begin van een lijn in. Lezen/schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public abstract byte getEndArrowheadWidth()
```

Retourneert of stelt de pijlpuntbreedte aan het einde van een lijn in. Lezen/schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retour:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public abstract void setEndArrowheadWidth(byte value)
```

Retourneert of stelt de pijlpuntbreedte aan het einde van een lijn in. Lezen/schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public abstract byte getBeginArrowheadLength()
```

Retourneert of stelt de pijlpuntlengte aan het begin van een lijn in. Lezen/schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retour:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public abstract void setBeginArrowheadLength(byte value)
```

Retourneert of stelt de pijlpuntlengte aan het begin van een lijn in. Lezen/schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public abstract byte getEndArrowheadLength()
```

Retourneert of stelt de pijlpuntlengte aan het einde van een lijn in. Lezen/schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retour:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```java
public abstract void setEndArrowheadLength(byte value)
```

Retourneert of stelt de pijlpuntlengte aan het einde van een lijn in. Lezen/schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

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