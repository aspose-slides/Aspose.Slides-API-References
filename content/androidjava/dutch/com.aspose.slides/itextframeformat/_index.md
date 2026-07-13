---
title: ITextFrameFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Bevat de opmaak eigenschappen van TextFrames.
type: docs
url: /nl/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Bevat de opmaak eigenschappen van TextFrame.
## Methoden

| Method | Description |
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
| [getWrapText()](#getWrapText--) | True als tekst wordt omgebroken bij de marges van TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True als tekst wordt omgebroken bij de marges van TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Retourneert of stelt verticale ankertekst in een TextFrame in. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Retourneert of stelt verticale ankertekst in een TextFrame in. |
| [getCenterText()](#getCenterText--) | Als NullableBool.True dan moet de tekst horizontaal gecentreerd in de doos worden. |
| [setCenterText(byte value)](#setCenterText-byte-) | Als NullableBool.True dan moet de tekst horizontaal gecentreerd in de doos worden. |
| [getTextVerticalType()](#getTextVerticalType--) | Bepaalt de tekstoriëntatie. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bepaalt de tekstoriëntatie. |
| [getAutofitType()](#getAutofitType--) | Retourneert of stelt de autofit-modus van de tekst in. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Retourneert of stelt de autofit-modus van de tekst in. |
| [getColumnCount()](#getColumnCount--) | Retourneert of stelt het aantal kolommen in het tekstgebied in. |
| [setColumnCount(int value)](#setColumnCount-int-) | Retourneert of stelt het aantal kolommen in het tekstgebied in. |
| [getColumnSpacing()](#getColumnSpacing--) | Retourneert of stelt de ruimte tussen tekstreeks kolommen in het tekstgebied in (in punten). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Retourneert of stelt de ruimte tussen tekstreeks kolommen in het tekstgebied in (in punten). |
| [getThreeDFormat()](#getThreeDFormat--) | Retourneert het ThreeDFormat-object dat de 3D-effecteigenschappen voor een tekst representeert. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Retourneert of stelt in dat tekst volledig uit de 3D-scène wordt gehouden. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Retourneert of stelt in dat tekst volledig uit de 3D-scène wordt gehouden. |
| [getRotationAngle()](#getRotationAngle--) | Specificeert de aangepaste rotatie die op de tekst binnen het omvattende vak wordt toegepast. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specificeert de aangepaste rotatie die op de tekst binnen het omvattende vak wordt toegepast. |
| [getTransform()](#getTransform--) | Haal of stel de vorm van tekstomslag op. |
| [setTransform(byte value)](#setTransform-byte-) | Haal of stel de vorm van tekstomslag op. |
| [getEffective()](#getEffective--) | Haal effectieve tekstframe-opmaakgegevens op met de toegepaste overerving. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Retourneert de stijl van de tekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retour:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Retourneert of stelt de linkermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Retour:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Retourneert of stelt de linkermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Retourneert of stelt de rechtermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Retour:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Retourneert of stelt de rechtermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Retourneert of stelt de bovenmarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Retour:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Retourneert of stelt de bovenmarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Retourneert of stelt de ondermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Retour:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Retourneert of stelt de ondermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True als tekst wordt omgebroken bij de marges van TextFrame. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True als tekst wordt omgebroken bij de marges van TextFrame. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Retourneert of stelt verticale ankertekst in een TextFrame in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retour:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Retourneert of stelt verticale ankertekst in een TextFrame in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Als NullableBool.True dan moet de tekst horizontaal gecentreerd in de doos worden. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Als NullableBool.True dan moet de tekst horizontaal gecentreerd in de doos worden. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Bepaalt de tekstoriëntatie. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en de aangepaste hoek in eigenschap RotationAngle. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retour:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Bepaalt de tekstoriëntatie. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en de aangepaste hoek in eigenschap RotationAngle. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Retourneert of stelt de autofit-modus van de tekst in. Lezen/Schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retour:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Retourneert of stelt de autofit-modus van de tekst in. Lezen/Schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Retourneert of stelt het aantal kolommen in het tekstgebied in. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent een ongedefinieerde waarde. Lezen/Schrijven int.

**Retour:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Retourneert of stelt het aantal kolommen in het tekstgebied in. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent een ongedefinieerde waarde. Lezen/Schrijven int.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Retourneert of stelt de ruimte tussen tekstreeks kolommen in het tekstgebied in (in punten). Dit geldt alleen wanneer er meer dan één kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Lezen/Schrijven double.

**Retour:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Retourneert of stelt de ruimte tussen tekstreeks kolommen in het tekstgebied in (in punten). Dit geldt alleen wanneer er meer dan één kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Retourneert het ThreeDFormat-object dat de 3D-effecteigenschappen voor een tekst representeert. Alleen-lezen [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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
>      // Stel camertype in
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retour:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Retourneert of stelt in dat tekst volledig uit de 3D-scène wordt gehouden. Lezen/Schrijven boolean.

**Retour:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Retourneert of stelt in dat tekst volledig uit de 3D-scène wordt gehouden. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Specificeert de aangepaste rotatie die op de tekst binnen het omvattende vak wordt toegepast. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat wil zeggen dat de vorm een rotatie kan hebben die toegevoegd wordt aan de rotatie van de tekst zelf. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in eigenschap TextVerticalType. Lezen/Schrijven float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Retour:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Specificeert de aangepaste rotatie die op de tekst binnen het omvattende vak wordt toegepast. Als deze niet is opgegeven, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel is opgegeven, wordt deze onafhankelijk van de vorm toegepast. Dat wil zeggen dat de vorm een rotatie kan hebben die toegevoegd wordt aan de rotatie van de tekst zelf. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in eigenschap TextVerticalType. Lezen/Schrijven float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Haal of stel de vorm van tekstomslag op. Lezen/Schrijven [TextShapeType](../../com.aspose.slides/textshapetype).

**Retour:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Haal of stel de vorm van tekstomslag op. Lezen/Schrijven [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Haal effectieve tekstframe-opmaakgegevens op met de toegepaste overerving.

**Retour:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).