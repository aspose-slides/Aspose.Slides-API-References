---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Innehåller formateringsegenskaperna för TextFrames.
type: docs
url: /sv/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Innehåller formateringsegenskaperna för TextFrame.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Returnerar textens stil. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller anger den vänstra marginalen (punkter) i en TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returnerar eller anger den vänstra marginalen (punkter) i en TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller anger den högra marginalen (punkter) i en TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returnerar eller anger den högra marginalen (punkter) i en TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returnerar eller anger den övre marginalen (punkter) i en TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returnerar eller anger den övre marginalen (punkter) i en TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returnerar eller anger den nedre marginalen (punkter) i en TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returnerar eller anger den nedre marginalen (punkter) i en TextFrame. |
| [getWrapText()](#getWrapText--) | Sant om texten radbryts vid TextFrames marginaler. |
| [setWrapText(byte value)](#setWrapText-byte-) | Sant om texten radbryts vid TextFrames marginaler. |
| [getAnchoringType()](#getAnchoringType--) | Returnerar eller anger vertikal ankartext i en TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returnerar eller anger vertikal ankartext i en TextFrame. |
| [getCenterText()](#getCenterText--) | Om NullableBool.True är sann ska texten centreras horisontellt i rutan. |
| [setCenterText(byte value)](#setCenterText-byte-) | Om NullableBool.True är sann ska texten centreras horisontellt i rutan. |
| [getTextVerticalType()](#getTextVerticalType--) | Bestämmer textorientering. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bestämmer textorientering. |
| [getAutofitType()](#getAutofitType--) | Returnerar eller anger textens autofit-läge. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returnerar eller anger textens autofit-läge. |
| [getColumnCount()](#getColumnCount--) | Returnerar eller anger antal kolumner i textområdet. |
| [setColumnCount(int value)](#setColumnCount-int-) | Returnerar eller anger antal kolumner i textområdet. |
| [getColumnSpacing()](#getColumnSpacing--) | Returnerar eller anger avståndet mellan textkolumner i textområdet (i punkter). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Returnerar eller anger avståndet mellan textkolumner i textområdet (i punkter). |
| [getThreeDFormat()](#getThreeDFormat--) | Returnerar ThreeDFormat-objektet som representerar 3d-effektegenskaper för en text. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Returnerar eller anger att texten hålls helt utanför 3D-scenen. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Returnerar eller anger att texten hålls helt utanför 3D-scenen. |
| [getRotationAngle()](#getRotationAngle--) | Anger den anpassade rotation som appliceras på texten inom den omgivande ramen. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Anger den anpassade rotation som appliceras på texten inom den omgivande ramen. |
| [getTransform()](#getTransform--) | Hämtar eller anger textomslutningsformen. |
| [setTransform(byte value)](#setTransform-byte-) | Hämtar eller anger textomslutningsformen. |
| [getEffective()](#getEffective--) | Hämtar effektiva formateringsdata för textramen med ärvd egenskap tillämpad. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Returnerar textens stil. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Returnerar eller anger den vänstra marginalen (punkter) i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Returnerar eller anger den vänstra marginalen (punkter) i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Returnerar eller anger den högra marginalen (punkter) i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Returnerar eller anger den högra marginalen (punkter) i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Returnerar eller anger den övre marginalen (punkter) i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Returnerar eller anger den övre marginalen (punkter) i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Returnerar eller anger den nedre marginalen (punkter) i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Returnerar eller anger den nedre marginalen (punkter) i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Sant om texten radbryts vid TextFrames marginaler. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Sant om texten radbryts vid TextFrames marginaler. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Returnerar eller anger vertikal ankartext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returnerar:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Returnerar eller anger vertikal ankartext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
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
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Bestämmer textorientering. Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och anpassad vinkel i egenskapen RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returnerar:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Bestämmer textorientering. Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och anpassad vinkel i egenskapen RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Returnerar eller anger textens autofit-läge. Läs/skriv [TextAutofitType](../../com.aspose.slides/textautofittype).

**Returnerar:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Returnerar eller anger textens autofit-läge. Läs/skriv [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Returnerar eller anger antal kolumner i textområdet. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Värde 0 betyder odefinierat värde. Läs/skriv int.

**Returnerar:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Returnerar eller anger antal kolumner i textområdet. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Värde 0 betyder odefinierat värde. Läs/skriv int.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Returnerar eller anger avståndet mellan textkolumner i textområdet (i punkter). Detta bör bara gälla när mer än 1 kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs/skriv double.

**Returnerar:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Returnerar eller anger avståndet mellan textkolumner i textområdet (i punkter). Detta bör bara gälla när mer än 1 kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Returnerar ThreeDFormat-objektet som representerar 3d-effektegenskaper för en text. Skrivskyddad [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Ställ in texttransformation
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Ställ in extrudering
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Ställ in kontur
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Ställ in djup
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Ställ in material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Ställ in belysning
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Ställ in kameratyp
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Returnerar:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Returnerar eller anger att texten hålls helt utanför 3D-scenen. Läs/skriv boolean.

**Returnerar:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Returnerar eller anger att texten hålls helt utanför 3D-scenen. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Anger den anpassade rotation som appliceras på texten inom den omgivande ramen. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Läs/skriv float.

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

Anger den anpassade rotation som appliceras på texten inom den omgivande ramen. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation sammanfattas från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Läs/skriv float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Hämtar eller anger textomslutningsformen. Läs/skriv [TextShapeType](../../com.aspose.slides/textshapetype).

**Returnerar:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Hämtar eller anger textomslutningsformen. Läs/skriv [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Hämtar effektiva formateringsdata för textramen med ärvd egenskap tillämpad.

**Returnerar:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).