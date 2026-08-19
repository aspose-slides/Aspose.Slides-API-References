---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /sv/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Representerar formateringsegenskaper för diagramtext-element.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Returnerar eller anger vertikal ankaretext i en TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returnerar eller anger vertikal ankaretext i en TextFrame. |
| [getCenterText()](#getCenterText--) | Om NullableBool.True är sann ska texten centreras horisontellt i rutan. |
| [setCenterText(byte value)](#setCenterText-byte-) | Om NullableBool.True är sann ska texten centreras horisontellt i rutan. |
| [getTextVerticalType()](#getTextVerticalType--) | Bestämmer textorientering. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bestämmer textorientering. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller anger vänster marginal (punkter) i en TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returnerar eller anger vänster marginal (punkter) i en TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller anger höger marginal (punkter) i en TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returnerar eller anger höger marginal (punkter) i en TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returnerar eller anger överkantsmarginal (punkter) i en TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returnerar eller anger överkantsmarginal (punkter) i en TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returnerar eller anger nederkantsmarginal (punkter) i en TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returnerar eller anger nederkantsmarginal (punkter) i en TextFrame. |
| [getWrapText()](#getWrapText--) | Sant om texten radbryts vid TextFrames marginaler. |
| [setWrapText(byte value)](#setWrapText-byte-) | Sant om texten radbryts vid TextFrames marginaler. |
| [getAutofitType()](#getAutofitType--) | Returnerar eller anger textens autofit-läge. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returnerar eller anger textens autofit-läge. |
| [getRotationAngle()](#getRotationAngle--) | Anger den anpassade rotation som tillämpas på texten inom den avgränsande rutan. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Anger den anpassade rotation som tillämpas på texten inom den avgränsande rutan. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Returnerar eller anger vertikal ankaretext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returnerar:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


Returnerar eller anger vertikal ankaretext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


Om NullableBool.True är sann ska texten centreras horisontellt i rutan. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


Om NullableBool.True är sann ska texten centreras horisontellt i rutan. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Bestämmer textorientering. Det resulterande värdet för visuell textrotation sammanfattas från denna egenskap och den anpassade vinkeln i egenskapen RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returnerar:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Bestämmer textorientering. Det resulterande värdet för visuell textrotation sammanfattas från denna egenskap och den anpassade vinkeln i egenskapen RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Returnerar eller anger vänster marginal (punkter) i en TextFrame. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv double.

**Returnerar:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Returnerar eller anger vänster marginal (punkter) i en TextFrame. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv double.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Returnerar eller anger höger marginal (punkter) i en TextFrame. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv double.

**Returnerar:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Returnerar eller anger höger marginal (punkter) i en TextFrame. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv double.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Returnerar eller anger överkantsmarginal (punkter) i en TextFrame. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv double.

**Returnerar:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Returnerar eller anger överkantsmarginal (punkter) i en TextFrame. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv double.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Returnerar eller anger nederkantsmarginal (punkter) i en TextFrame. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv double.

**Returnerar:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Returnerar eller anger nederkantsmarginal (punkter) i en TextFrame. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv double.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


Sant om texten radbryts vid TextFrames marginaler. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2007/2013). Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


Sant om texten radbryts vid TextFrames marginaler. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2007/2013). Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Returnerar eller anger textens autofit-läge. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv [TextAutofitType](../../com.aspose.slides/textautofittype).

**Returnerar:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


Returnerar eller anger textens autofit-läge. Ändring av denna egenskap kan endast påverka följande diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen påverkan på rendering). Läs/skriv [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


Anger den anpassade rotation som tillämpas på texten inom den avgränsande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver den rotation som appliceras på själva texten. Det resulterande värdet för visuell textrotation sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs/skriv float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Returnerar:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Anger den anpassade rotation som tillämpas på texten inom den avgränsande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver den rotation som appliceras på själva texten. Det resulterande värdet för visuell textrotation sammanfattas från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs/skriv float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |