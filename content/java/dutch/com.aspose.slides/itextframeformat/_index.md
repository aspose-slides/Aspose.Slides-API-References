---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Reference
description: Bevat de opmaak-eigenschappen van TextFrames.
type: docs
url: /nl/com.aspose.slides/itextframeformat/
---
```
public interface ITextFrameFormat
```

Bevat de opmaak-eigenschappen van de TextFrame.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Retourneert de stijl van de tekst. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert of stelt de linkermarge (punten) in een TextFrame in. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Retourneert of stelt de linkermarge (punten) in een TextFrame in. |
| [getMarginRight()](#getMarginRight--) | Retourneert of stelt de rechtermarge (punten) in een TextFrame in. |
| [setMarginRight(double value)](#setMarginRight-double-) | Retourneert of stelt de rechtermarge (punten) in een TextFrame in. |
| [getMarginTop()](#getMarginTop--) | Retourneert of stelt de bovenmarge (punten) in een TextFrame in. |
| [setMarginTop(double value)](#setMarginTop-double-) | Retourneert of stelt de bovenmarge (punten) in een TextFrame in. |
| [getMarginBottom()](#getMarginBottom--) | Retourneert of stelt de ondermarge (punten) in een TextFrame in. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Retourneert of stelt de ondermarge (punten) in een TextFrame in. |
| [getWrapText()](#getWrapText--) | Waar als tekst wordt afgebroken bij de marges van de TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Waar als tekst wordt afgebroken bij de marges van de TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Retourneert of stelt verticale ankertekst in een TextFrame in. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Retourneert of stelt verticale ankertekst in een TextFrame in. |
| [getCenterText()](#getCenterText--) | Als NullableBool.True, dan moet de tekst horizontaal gecentreerd worden in de doos. |
| [setCenterText(byte value)](#setCenterText-byte-) | Als NullableBool.True, dan moet de tekst horizontaal gecentreerd worden in de doos. |
| [getTextVerticalType()](#getTextVerticalType--) | Bepaalt de tekstoriëntatie. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bepaalt de tekstoriëntatie. |
| [getAutofitType()](#getAutofitType--) | Retourneert of stelt de autofit-modus van de tekst in. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Retourneert of stelt de autofit-modus van de tekst in. |
| [getColumnCount()](#getColumnCount--) | Retourneert of stelt het aantal kolommen in het tekstgebied in. |
| [setColumnCount(int value)](#setColumnCount-int-) | Retourneert of stelt het aantal kolommen in het tekstgebied in. |
| [getColumnSpacing()](#getColumnSpacing--) | Retourneert of stelt de ruimte tussen tekstkolommen in het tekstgebied in (in punten). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Retourneert of stelt de ruimte tussen tekstkolommen in het tekstgebied in (in punten). |
| [getThreeDFormat()](#getThreeDFormat--) | Retourneert het ThreeDFormat-object dat de 3D-effecteigenschappen voor een tekst vertegenwoordigt. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Retourneert of stelt in dat de tekst volledig buiten de 3D-scene gehouden wordt. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Retourneert of stelt in dat de tekst volledig buiten de 3D-scene gehouden wordt. |
| [getRotationAngle()](#getRotationAngle--) | Specificeert de aangepaste rotatie die op de tekst binnen de begrenzingsdoos wordt toegepast. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specificeert de aangepaste rotatie die op de tekst binnen de begrenzingsdoos wordt toegepast. |
| [getTransform()](#getTransform--) | Haalt de vorm voor tekstomslag op of stelt deze in. |
| [setTransform(byte value)](#setTransform-byte-) | Haalt de vorm voor tekstomslag op of stelt deze in. |
| [getEffective()](#getEffective--) | Haalt effectieve opmaakgegevens van het tekstframe op met de toegepaste overerving. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```


Retourneert de stijl van de tekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Retourneert of stelt de linkermarge (punten) in een TextFrame in. Lezen/schrijven double.

**Retourneert:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Retourneert of stelt de linkermarge (punten) in een TextFrame in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Retourneert of stelt de rechtermarge (punten) in een TextFrame in. Lezen/schrijven double.

**Retourneert:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Retourneert of stelt de rechtermarge (punten) in een TextFrame in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Retourneert of stelt de bovenmarge (punten) in een TextFrame in. Lezen/schrijven double.

**Retourneert:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Retourneert of stelt de bovenmarge (punten) in een TextFrame in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Retourneert of stelt de ondermarge (punten) in een TextFrame in. Lezen/schrijven double.

**Retourneert:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Retourneert of stelt de ondermarge (punten) in een TextFrame in. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


Waar als tekst wordt afgebroken bij de marges van de TextFrame. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


Waar als tekst wordt afgebroken bij de marges van de TextFrame. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Retourneert of stelt verticale ankertekst in een TextFrame in. Lezen/schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retourneert:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


Retourneert of stelt verticale ankertekst in een TextFrame in. Lezen/schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


Als NullableBool.True, dan moet de tekst horizontaal gecentreerd worden in de doos. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


Als NullableBool.True, dan moet de tekst horizontaal gecentreerd worden in de doos. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Bepaalt de tekstoriëntatie. De geresulteerde waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en de vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lezen/schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retourneert:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Bepaalt de tekstoriëntatie. De geresulteerde waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en de vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lezen/schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Retourneert of stelt de autofit-modus van de tekst in. Lezen/schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retourneert:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


Retourneert of stelt de autofit-modus van de tekst in. Lezen/schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Retourneert of stelt het aantal kolommen in het tekstgebied in. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent ongedefinieerde waarde. Lezen/schrijven int.

**Retourneert:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```


Retourneert of stelt het aantal kolommen in het tekstgebied in. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent ongedefinieerde waarde. Lezen/schrijven int.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```


Retourneert of stelt de ruimte tussen tekstkolommen in het tekstgebied in (in punten). Dit geldt alleen wanneer er meer dan één kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Lezen/schrijven double.

**Retourneert:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```


Retourneert of stelt de ruimte tussen tekstkolommen in het tekstgebied in (in punten). Dit geldt alleen wanneer er meer dan één kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


Retourneert het ThreeDFormat-object dat de 3D-effecteigenschappen voor een tekst vertegenwoordigt. Alleen-lezen [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Stel teksttransformatie in
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Stel extrusie in
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Stel contour in
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Stel diepte in
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Stel materiaal in
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Stel verlichting in
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Stel cameratype in
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```


Retourneert of stelt in dat de tekst volledig buiten de 3D-scene gehouden wordt. Lezen/schrijven boolean.

**Retourneert:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```


Retourneert of stelt in dat de tekst volledig buiten de 3D-scene gehouden wordt. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


Specificeert de aangepaste rotatie die op de tekst binnen de begrenzingsdoos wordt toegepast. Indien niet gespecificeerd, wordt de rotatie van de bijbehorende vorm gebruikt. Indien wel gespecificeerd, wordt deze onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben, naast de rotatie die op de tekst zelf wordt toegepast. De geresulteerde waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lezen/schrijven float.

--------------------

> ```
> Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft gekregen. 
>  Daarnaast heeft de tekst zelf een rotatie van -90 graden 
>  tegen de klok in gekregen. Dan zou de resulterende vorm lijken te
>  gedraaid zijn, maar de tekst erin zou lijken alsof hij helemaal niet gedraaid is.
```

**Retourneert:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Specificeert de aangepaste rotatie die op de tekst binnen de begrenzingsdoos wordt toegepast. Indien niet gespecificeerd, wordt de rotatie van de bijbehorende vorm gebruikt. Indien wel gespecificeerd, wordt deze onafhankelijk van de vorm toegepast. Dat betekent dat de vorm een rotatie kan hebben, naast de rotatie die op de tekst zelf wordt toegepast. De geresulteerde waarde van de visuele tekstrotatie wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in de eigenschap TextVerticalType. Lezen/schrijven float.

--------------------

> ```
> Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft gekregen. 
>  Daarnaast heeft de tekst zelf een rotatie van -90 graden 
>  tegen de klok in gekregen. Dan zou de resulterende vorm lijken te
>  gedraaid zijn, maar de tekst erin zou lijken alsof hij helemaal niet gedraaid is.
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```


Haalt de vorm voor tekstomslag op of stelt deze in. Lezen/schrijven [TextShapeType](../../com.aspose.slides/textshapetype).

**Retourneert:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```


Haalt de vorm voor tekstomslag op of stelt deze in. Lezen/schrijven [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```


Haalt effectieve opmaakgegevens van het tekstframe op met de toegepaste overerving.

**Retourneert:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).