---
title: LineFormat
second_title: Aspose.Slides voor Android via Java API Referentie
description: Stelt het formaat van een lijn voor.
type: docs
url: /nl/com.aspose.slides/lineformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILineFormat](../../com.aspose.slides/ilineformat)
```
public final class LineFormat extends PVIObject implements ILineFormat
```

Stelt het formaat van een lijn voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) |  |
| [isFormatNotDefined()](#isFormatNotDefined--) | Retourneert true als het lijnformaat niet is gedefinieerd (net aangemaakt, standaard). |
| [getFillFormat()](#getFillFormat--) | Retourneert het opvulformaat van een lijn. |
| [getSketchFormat()](#getSketchFormat--) | Retourneert het schetsformaat van een lijn. |
| [getWidth()](#getWidth--) | Retourneert of stelt de breedte van een lijn in. |
| [setWidth(double value)](#setWidth-double-) | Retourneert of stelt de breedte van een lijn in. |
| [getDashStyle()](#getDashStyle--) | Retourneert of stelt de streepjesstijl van de lijn in. |
| [setDashStyle(byte value)](#setDashStyle-byte-) | Retourneert of stelt de streepjesstijl van de lijn in. |
| [getCustomDashPattern()](#getCustomDashPattern--) | Retourneert of stelt het aangepaste streepjespatroon in. |
| [setCustomDashPattern(float[] value)](#setCustomDashPattern-float---) | Retourneert of stelt het aangepaste streepjespatroon in. |
| [getCapStyle()](#getCapStyle--) | Retourneert of stelt de lijnkapstijl in. |
| [setCapStyle(byte value)](#setCapStyle-byte-) | Retourneert of stelt de lijnkapstijl in. |
| [getStyle()](#getStyle--) | Retourneert of stelt de lijnstijl in. |
| [setStyle(byte value)](#setStyle-byte-) | Retourneert of stelt de lijnstijl in. |
| [getAlignment()](#getAlignment--) | Retourneert of stelt de lijnuitlijning in. |
| [setAlignment(byte value)](#setAlignment-byte-) | Retourneert of stelt de lijnuitlijning in. |
| [getJoinStyle()](#getJoinStyle--) | Retourneert of stelt de verbindingsstijl van de lijnen in. |
| [setJoinStyle(byte value)](#setJoinStyle-byte-) | Retourneert of stelt de verbindingsstijl van de lijnen in. |
| [getMiterLimit()](#getMiterLimit--) | Retourneert of stelt de miterlimiet van een lijn in. |
| [setMiterLimit(float value)](#setMiterLimit-float-) | Retourneert of stelt de miterlimiet van een lijn in. |
| [getBeginArrowheadStyle()](#getBeginArrowheadStyle--) | Retourneert of stelt de pijlstijl aan het begin van een lijn in. |
| [setBeginArrowheadStyle(byte value)](#setBeginArrowheadStyle-byte-) | Retourneert of stelt de pijlstijl aan het begin van een lijn in. |
| [getEndArrowheadStyle()](#getEndArrowheadStyle--) | Retourneert of stelt de pijlstijl aan het einde van een lijn in. |
| [setEndArrowheadStyle(byte value)](#setEndArrowheadStyle-byte-) | Retourneert of stelt de pijlstijl aan het einde van een lijn in. |
| [getBeginArrowheadWidth()](#getBeginArrowheadWidth--) | Retourneert of stelt de pijlbreedte aan het begin van een lijn in. |
| [setBeginArrowheadWidth(byte value)](#setBeginArrowheadWidth-byte-) | Retourneert of stelt de pijlbreedte aan het begin van een lijn in. |
| [getEndArrowheadWidth()](#getEndArrowheadWidth--) | Retourneert of stelt de pijlbreedte aan het einde van een lijn in. |
| [setEndArrowheadWidth(byte value)](#setEndArrowheadWidth-byte-) | Retourneert of stelt de pijlbreedte aan het einde van een lijn in. |
| [getBeginArrowheadLength()](#getBeginArrowheadLength--) | Retourneert of stelt de pijllengte aan het begin van een lijn in. |
| [setBeginArrowheadLength(byte value)](#setBeginArrowheadLength-byte-) | Retourneert of stelt de pijllengte aan het begin van een lijn in. |
| [getEndArrowheadLength()](#getEndArrowheadLength--) | Retourneert of stelt de pijllengte aan het einde van een lijn in. |
| [setEndArrowheadLength(byte value)](#setEndArrowheadLength-byte-) | Retourneert of stelt de pijllengte aan het einde van een lijn in. |
| [equals(ILineFormat lineFormat)](#equals-com.aspose.slides.ILineFormat-) | Bepaalt of de twee LineFormat-instanties gelijk zijn. |
| [getEffective()](#getEffective--) | Haalt de effectieve lijnopmaakinformatie op met de hier toegepaste erfelijkheid. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versie. Alleen-lezen long.

**Retourneert:**
long
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Vergelijkt met het opgegeven object.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| obj | java.lang.Object |  |

**Retourneert:**
boolean
### isFormatNotDefined() {#isFormatNotDefined--}
```
public final boolean isFormatNotDefined()
```


Retourneert true als het lijnformaat niet is gedefinieerd (net aangemaakt, standaard). Alleen-lezen boolean.

**Retourneert:**
boolean
### getFillFormat() {#getFillFormat--}
```
public final ILineFillFormat getFillFormat()
```


Retourneert het opvulformaat van een lijn. Alleen-lezen [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Retourneert:**
[ILineFillFormat](../../com.aspose.slides/ilinefillformat)
### getSketchFormat() {#getSketchFormat--}
```
public final ISketchFormat getSketchFormat()
```


Retourneert het schetsformaat van een lijn. Alleen-lezen [ILineFillFormat](../../com.aspose.slides/ilinefillformat).

**Retourneert:**
[ISketchFormat](../../com.aspose.slides/isketchformat)
### getWidth() {#getWidth--}
```
public final double getWidth()
```


Retourneert of stelt de breedte van een lijn in. Lezen/Schrijven double .

**Retourneert:**
double
### setWidth(double value) {#setWidth-double-}
```
public final void setWidth(double value)
```


Retourneert of stelt de breedte van een lijn in. Lezen/Schrijven double .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getDashStyle() {#getDashStyle--}
```
public final byte getDashStyle()
```


Retourneert of stelt de lijnstreepjesstijl in. Lezen/Schrijven [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Retourneert:**
byte
### setDashStyle(byte value) {#setDashStyle-byte-}
```
public final void setDashStyle(byte value)
```


Retourneert of stelt de lijnstreepjesstijl in. Lezen/Schrijven [LineDashStyle](../../com.aspose.slides/linedashstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getCustomDashPattern() {#getCustomDashPattern--}
```
public final float[] getCustomDashPattern()
```


Retourneert of stelt het aangepaste streepjespatroon in. Lezen/Schrijven float[] .

**Retourneert:**
float[]
### setCustomDashPattern(float[] value) {#setCustomDashPattern-float---}
```
public final void setCustomDashPattern(float[] value)
```


Retourneert of stelt het aangepaste streepjespatroon in. Lezen/Schrijven float[] .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float[] |  |
### getCapStyle() {#getCapStyle--}
```
public final byte getCapStyle()
```


Retourneert of stelt de lijnkapstijl in. Lezen/Schrijven [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Retourneert:**
byte
### setCapStyle(byte value) {#setCapStyle-byte-}
```
public final void setCapStyle(byte value)
```


Retourneert of stelt de lijnkapstijl in. Lezen/Schrijven [LineCapStyle](../../com.aspose.slides/linecapstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getStyle() {#getStyle--}
```
public final byte getStyle()
```


Retourneert of stelt de lijnstijl in. Lezen/Schrijven [LineStyle](../../com.aspose.slides/linestyle).

**Retourneert:**
byte
### setStyle(byte value) {#setStyle-byte-}
```
public final void setStyle(byte value)
```


Retourneert of stelt de lijnstijl in. Lezen/Schrijven [LineStyle](../../com.aspose.slides/linestyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getAlignment() {#getAlignment--}
```
public final byte getAlignment()
```


Retourneert of stelt de lijnuitlijning in. Lezen/Schrijven [LineAlignment](../../com.aspose.slides/linealignment).

**Retourneert:**
byte
### setAlignment(byte value) {#setAlignment-byte-}
```
public final void setAlignment(byte value)
```


Retourneert of stelt de lijnuitlijning in. Lezen/Schrijven [LineAlignment](../../com.aspose.slides/linealignment).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getJoinStyle() {#getJoinStyle--}
```
public final byte getJoinStyle()
```


Retourneert of stelt de verbindingsstijl van de lijnen in. Lezen/Schrijven [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Retourneert:**
byte
### setJoinStyle(byte value) {#setJoinStyle-byte-}
```
public final void setJoinStyle(byte value)
```


Retourneert of stelt de verbindingsstijl van de lijnen in. Lezen/Schrijven [LineJoinStyle](../../com.aspose.slides/linejoinstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getMiterLimit() {#getMiterLimit--}
```
public final float getMiterLimit()
```


Retourneert of stelt de miterlimiet van een lijn in. Lezen/Schrijven float .

**Retourneert:**
float
### setMiterLimit(float value) {#setMiterLimit-float-}
```
public final void setMiterLimit(float value)
```


Retourneert of stelt de miterlimiet van een lijn in. Lezen/Schrijven float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getBeginArrowheadStyle() {#getBeginArrowheadStyle--}
```
public final byte getBeginArrowheadStyle()
```


Retourneert of stelt de pijlstijl aan het begin van een lijn in. Lezen/Schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retourneert:**
byte
### setBeginArrowheadStyle(byte value) {#setBeginArrowheadStyle-byte-}
```
public final void setBeginArrowheadStyle(byte value)
```


Retourneert of stelt de pijlstijl aan het begin van een lijn in. Lezen/Schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadStyle() {#getEndArrowheadStyle--}
```
public final byte getEndArrowheadStyle()
```


Retourneert of stelt de pijlstijl aan het einde van een lijn in. Lezen/Schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Retourneert:**
byte
### setEndArrowheadStyle(byte value) {#setEndArrowheadStyle-byte-}
```
public final void setEndArrowheadStyle(byte value)
```


Retourneert of stelt de pijlstijl aan het einde van een lijn in. Lezen/Schrijven [LineArrowheadStyle](../../com.aspose.slides/linearrowheadstyle).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadWidth() {#getBeginArrowheadWidth--}
```
public final byte getBeginArrowheadWidth()
```


Retourneert of stelt de pijlbreedte aan het begin van een lijn in. Lezen/Schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retourneert:**
byte
### setBeginArrowheadWidth(byte value) {#setBeginArrowheadWidth-byte-}
```
public final void setBeginArrowheadWidth(byte value)
```


Retourneert of stelt de pijlbreedte aan het begin van een lijn in. Lezen/Schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadWidth() {#getEndArrowheadWidth--}
```
public final byte getEndArrowheadWidth()
```


Retourneert of stelt de pijlbreedte aan het einde van een lijn in. Lezen/Schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Retourneert:**
byte
### setEndArrowheadWidth(byte value) {#setEndArrowheadWidth-byte-}
```
public final void setEndArrowheadWidth(byte value)
```


Retourneert of stelt de pijlbreedte aan het einde van een lijn in. Lezen/Schrijven [LineArrowheadWidth](../../com.aspose.slides/linearrowheadwidth).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getBeginArrowheadLength() {#getBeginArrowheadLength--}
```
public final byte getBeginArrowheadLength()
```


Retourneert of stelt de pijllengte aan het begin van een lijn in. Lezen/Schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retourneert:**
byte
### setBeginArrowheadLength(byte value) {#setBeginArrowheadLength-byte-}
```
public final void setBeginArrowheadLength(byte value)
```


Retourneert of stelt de pijllengte aan het begin van een lijn in. Lezen/Schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getEndArrowheadLength() {#getEndArrowheadLength--}
```
public final byte getEndArrowheadLength()
```


Retourneert of stelt de pijllengte aan het einde van een lijn in. Lezen/Schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Retourneert:**
byte
### setEndArrowheadLength(byte value) {#setEndArrowheadLength-byte-}
```
public final void setEndArrowheadLength(byte value)
```


Retourneert of stelt de pijllengte aan het einde van een lijn in. Lezen/Schrijven [LineArrowheadLength](../../com.aspose.slides/linearrowheadlength).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### equals(ILineFormat lineFormat) {#equals-com.aspose.slides.ILineFormat-}
```
public final boolean equals(ILineFormat lineFormat)
```


Bepaalt of de twee LineFormat-instanties gelijk zijn.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| lineFormat | [ILineFormat](../../com.aspose.slides/ilineformat) | De LineFormat om te vergelijken met de huidige LineFormat. |

**Retourneert:**
boolean - **true** if the specified LineFormat is equal to the current LineFormat; otherwise, **false**.
### getEffective() {#getEffective--}
```
public final ILineFormatEffectiveData getEffective()
```


Haalt de effectieve lijnopmaakinformatie op met de hier toegepaste erfelijkheid.

--------------------

> ```
> Dit voorbeeld toont het ophalen van de effectieve lijnformateigenschappen van een vorm.
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

**Retourneert:**
[ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata) - A [ILineFormatEffectiveData](../../com.aspose.slides/ilineformateffectivedata).