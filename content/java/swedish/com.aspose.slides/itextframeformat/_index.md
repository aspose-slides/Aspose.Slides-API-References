---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: Contains the TextFrames formatting properties.
type: docs
url: /sv/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Innehåller TextFrames formateringsegenskaper.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Returns text's style. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin (points) in a TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returns or sets the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin (points) in a TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returns or sets the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns or sets the top margin (points) in a TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returns or sets the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns or sets the bottom margin (points) in a TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returns or sets the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | True if text is wrapped at TextFrame's margins. |
| [setWrapText(byte value)](#setWrapText-byte-) | True if text is wrapped at TextFrame's margins. |
| [getAnchoringType()](#getAnchoringType--) | Returns or sets vertical anchor text in a TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returns or sets vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | If NullableBool.True then text should be centered in box horizontally. |
| [setCenterText(byte value)](#setCenterText-byte-) | If NullableBool.True then text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Determines text orientation. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determines text orientation. |
| [getAutofitType()](#getAutofitType--) | Returns or sets text's autofit mode. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returns or sets text's autofit mode. |
| [getColumnCount()](#getColumnCount--) | Returns or sets number of columns in the text area. |
| [setColumnCount(int value)](#setColumnCount-int-) | Returns or sets number of columns in the text area. |
| [getColumnSpacing()](#getColumnSpacing--) | Returns or sets the space between text columns in the text area (in points). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Returns or sets the space between text columns in the text area (in points). |
| [getThreeDFormat()](#getThreeDFormat--) | Returns the ThreeDFormat object that represents 3d effect properties for a text. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Returns or set keeping text out of 3D scene entirely. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Returns or set keeping text out of 3D scene entirely. |
| [getRotationAngle()](#getRotationAngle--) | Specifies the custom rotation that is being applied to the text within the bounding box. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specifies the custom rotation that is being applied to the text within the bounding box. |
| [getTransform()](#getTransform--) | Gets or sets text wrapping shape. |
| [setTransform(byte value)](#setTransform-byte-) | Gets or sets text wrapping shape. |
| [getEffective()](#getEffective--) | Gets effective text frame formatting data with the inheritance applied. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```


Returnerar textens stil. Läs-endast [ITextStyle](../../com.aspose.slides/itextstyle).

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


Sant om texten är radbruten vid TextFrames marginaler. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


Sant om texten är radbruten vid TextFrames marginaler. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Returnerar eller anger vertikal förankringstext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returnerar:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


Returnerar eller anger vertikal förankringstext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


Om NullableBool.True ska texten centreras horisontellt i rutan. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


Om NullableBool.True ska texten centreras horisontellt i rutan. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Bestämmer textorientering. Det resulterande värdet av visuell textrotation sammanfattat från denna egenskap och anpassad vinkel i egenskap RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returnerar:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Bestämmer textorientering. Det resulterande värdet av visuell textrotation sammanfattat från denna egenskap och anpassad vinkel i egenskap RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

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


Returnerar eller anger avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast tillämpas när mer än 1 kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs/skriv double.

**Returnerar:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```


Returnerar eller anger avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast tillämpas när mer än 1 kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


Returnerar ThreeDFormat-objektet som representerar 3D-effektegenskaper för en text. Läs-endast [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Ställ in texttransformation
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Ställ in extrusion
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


Returnerar eller anger att hålla texten helt ute från 3D-scenen. Läs/skriv boolean.

**Returnerar:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```


Returnerar eller anger att hålla texten helt ute från 3D-scenen. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


Anger den anpassade rotation som tillämpas på texten inom den omgivande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det betyder att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation sammanfattat från denna egenskap och fördefinierad vertikal typ i egenskap TextVerticalType. Läs/skriv float.

--------------------

> ```
> Tänk på fallet där en form har en rotation på 90 grader medurs applicerad på den. 
>  Utöver detta har själva textkroppen en rotation på -90 grader 
>  moturs applicerad på den. Då skulle den resulterande formen verka att
>  vara roterad men texten inom den skulle verka som om den inte alls roterats.
> ```


**Returnerar:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Anger den anpassade rotation som tillämpas på texten inom den omgivande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det betyder att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation sammanfattat från denna egenskap och fördefinierad vertikal typ i egenskap TextVerticalType. Läs/skriv float.

--------------------

> ```
> Tänk på fallet där en form har en rotation på 90 grader medurs applicerad på den. 
>  Utöver detta har själva textkroppen en rotation på -90 grader 
>  moturs applicerad på den. Då skulle den resulterande formen verka att
>  vara roterad men texten inom den skulle verka som om den inte alls roterats.
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```


Hämtar eller anger textomslagningsformen. Läs/skriv [TextShapeType](../../com.aspose.slides/textshapetype).

**Returnerar:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```


Hämtar eller anger textomslagningsformen. Läs/skriv [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```


Hämtar effektiv textramformateringsdata med ärftlighet tillämpad.

**Returnerar:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).