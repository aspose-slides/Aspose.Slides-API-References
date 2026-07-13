---
title: IChartTextBlockFormat
second_title: Aspose.Slides för Android via Java API-referens
description: Representerar formateringsegenskaper för diagramtextelement.
type: docs
url: /sv/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Representerar formateringsegenskaper för diagramtextelement.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Returnerar eller anger vertikal ankartext i en TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returnerar eller anger vertikal ankartext i en TextFrame. |
| [getCenterText()](#getCenterText--) | Om NullableBool.True är true ska texten centrerad i boxen horisontellt. |
| [setCenterText(byte value)](#setCenterText-byte-) | Om NullableBool.True är true ska texten centrerad i boxen horisontellt. |
| [getTextVerticalType()](#getTextVerticalType--) | Bestämmer textorientering. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bestämmer textorientering. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller anger vänster marginal (punkter) i en TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returnerar eller anger vänster marginal (punkter) i en TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller anger höger marginal (punkter) i en TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returnerar eller anger höger marginal (punkter) i en TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returnerar eller anger övre marginal (punkter) i en TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returnerar eller anger övre marginal (punkter) i en TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returnerar eller anger nedre marginal (punkter) i en TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returnerar eller anger nedre marginal (punkter) i en TextFrame. |
| [getWrapText()](#getWrapText--) | Sant om texten radbryts vid TextFrames marginaler. |
| [setWrapText(byte value)](#setWrapText-byte-) | Sant om texten radbryts vid TextFrames marginaler. |
| [getAutofitType()](#getAutofitType--) | Returnerar eller anger textens autofit-läge. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returnerar eller anger textens autofit-läge. |
| [getRotationAngle()](#getRotationAngle--) | Anger den anpassade rotationen som tillämpas på texten inom den omgivande rutan. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Anger den anpassade rotationen som tillämpas på texten inom den omgivande rutan. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Returnerar eller anger vertikal ankartext i en TextFrame. Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returnerar:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Returnerar eller anger vertikal ankartext i en TextFrame. Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Om NullableBool.True är true ska texten centrerad i boxen horisontellt. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Om NullableBool.True är true ska texten centrerad i boxen horisontellt. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Bestämmer textorientering. Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och anpassad vinkel i egenskapen RotationAngle. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returnerar:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Bestämmer textorientering. Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och anpassad vinkel i egenskapen RotationAngle. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Returnerar eller anger vänster marginal (punkter) i en TextFrame. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write double.

**Returnerar:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Returnerar eller anger vänster marginal (punkter) i en TextFrame. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write double.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Returnerar eller anger höger marginal (punkter) i en TextFrame. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write double.

**Returnerar:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Returnerar eller anger höger marginal (punkter) i en TextFrame. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write double.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Returnerar eller anger övre marginal (punkter) i en TextFrame. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write double.

**Returnerar:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Returnerar eller anger övre marginal (punkter) i en TextFrame. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write double.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Returnerar eller anger nedre marginal (punkter) i en TextFrame. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write double.

**Returnerar:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Returnerar eller anger nedre marginal (punkter) i en TextFrame. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write double.

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Sant om texten radbryts vid TextFrames marginaler. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2007/2013). Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Sant om texten radbryts vid TextFrames marginaler. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2007/2013). Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Returnerar eller anger textens autofit-läge. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write [TextAutofitType](../../com.aspose.slides/textautofittype).

**Returnerar:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Returnerar eller anger textens autofit-läge. Ändring av denna egenskap kan ha viss påverkan endast för dessa diagramdelar: DataLabel och DataLabelFormat (fullt stöd i PowerPoint 2013; i PowerPoint 2007 har ingen effekt för rendering). Read/write [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Anger den anpassade rotationen som tillämpas på texten inom den omgivande rutan. Om den inte är angiven används rotationen för den medföljande formen. Om den är angiven tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation applicerad utöver att texten själv har en rotation applicerad. Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Read/write float.

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

Anger den anpassade rotationen som tillämpas på texten inom den omgivande rutan. Om den inte är angiven används rotationen för den medföljande formen. Om den är angiven tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation applicerad utöver att texten själv har en rotation applicerad. Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Read/write float.

--------------------

> ```
> Tänk på fallet där en form har en rotation på 90 grader medurs applicerad på den. 
>  Utöver detta har själva textkroppen en rotation på -90 grader 
>  moturs applicerad på den. Då skulle den resulterande formen verka
>  rotera men texten inom den skulle verka som om den inte hade roterats alls.
> ```


**Parametrar:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |