---
title: TextFrameFormat
second_title: Aspose.Slides voor Java API-referentie
description: Bevat de formatTextFrameFormatting-eigenschappen van TextFrames.
type: docs
url: /nl/com.aspose.slides/textframeformat/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Bevat de eigenschappen van formatTextFrameFormatting van TextFrame.

## Constructors

| Constructor | Description |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Initialiseert een nieuwe instantie van de klasse [TextFrameFormat](../../com.aspose.slides/textframeformat). |

## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Retourneert de stijl van de tekst. |
| [getThreeDFormat()](#getThreeDFormat--) | Retourneert het ThreeDFormat-object dat de 3D-effecteigenschappen voor een tekst representeert. |
| [getMarginLeft()](#getMarginLeft--) | Retourneert of stelt de linkermarge (punten) in een TextFrame in. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Retourneert of stelt de linkermarge (punten) in een TextFrame in. |
| [getMarginRight()](#getMarginRight--) | Retourneert of stelt de rechtermarge (punten) in een TextFrame in. |
| [setMarginRight(double value)](#setMarginRight-double-) | Retourneert of stelt de rechtermarge (punten) in een TextFrame in. |
| [getMarginTop()](#getMarginTop--) | Retourneert of stelt de bovenmarge (punten) in een TextFrame in. |
| [setMarginTop(double value)](#setMarginTop-double-) | Retourneert of stelt de bovenmarge (punten) in een TextFrame in. |
| [getMarginBottom()](#getMarginBottom--) | Retourneert of stelt de ondermarge (punten) in een TextFrame in. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Retourneert of stelt de ondermarge (punten) in een TextFrame in. |
| [getWrapText()](#getWrapText--) | Waar als tekst wordt afgebroken bij de marges van TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Waar als tekst wordt afgebroken bij de marges van TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Retourneert of stelt verticale ankertekst in een TextFrame in. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Retourneert of stelt verticale ankertekst in een TextFrame in. |
| [getCenterText()](#getCenterText--) | Als NullableBool.True, dan moet de tekst horizontaal gecentreerd zijn in het vak. |
| [setCenterText(byte value)](#setCenterText-byte-) | Als NullableBool.True, dan moet de tekst horizontaal gecentreerd zijn in het vak. |
| [getTextVerticalType()](#getTextVerticalType--) | Bepaalt de tekstoriëntatie. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bepaalt de tekstoriëntatie. |
| [getAutofitType()](#getAutofitType--) | Retourneert of stelt de autofit-modus van de tekst in. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Retourneert of stelt de autofit-modus van de tekst in. |
| [getColumnCount()](#getColumnCount--) | Retourneert of stelt het aantal kolommen in het tekstergebied in. |
| [setColumnCount(int value)](#setColumnCount-int-) | Retourneert of stelt het aantal kolommen in het tekstergebied in. |
| [getColumnSpacing()](#getColumnSpacing--) | Retourneert of stelt de ruimte tussen tekstkolommen in het tekstergebied in (in punten). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Retourneert of stelt de ruimte tussen tekstkolommen in het tekstergebied in (in punten). |
| [getRotationAngle()](#getRotationAngle--) | Specificeert een aangepaste rotatie die op de tekst binnen de begrenzende doos wordt toegepast. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specificeert een aangepaste rotatie die op de tekst binnen de begrenzende doos wordt toegepast. |
| [getTransform()](#getTransform--) | Haalt op of stelt de tekstomslagvorm in. |
| [setTransform(byte value)](#setTransform-byte-) | Haalt op of stelt de tekstomslagvorm in. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Haalt op of stelt in dat de tekst plat blijft zelfs als een 3D-rotatie-effect is toegepast. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Haalt op of stelt in dat de tekst plat blijft zelfs als een 3D-rotatie-effect is toegepast. |
| [getEffective()](#getEffective--) | Haalt de effectieve tekstframe-opmaakgegevens op met de aangebrachte overerving. |

### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Initialiseert een nieuwe instantie van de klasse [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retourneert:**
long

### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Retourneert de stijl van de tekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retourneert:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
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
>      // Stel cameratype in
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Retourneert of stelt de linkermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Retourneert:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Retourneert of stelt de linkermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Retourneert of stelt de rechtermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Retourneert:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Retourneert of stelt de rechtermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Retourneert of stelt de bovenmarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Retourneert:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Retourneert of stelt de bovenmarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Retourneert of stelt de ondermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Retourneert:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Retourneert of stelt de ondermarge (punten) in een TextFrame in. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

Waar als tekst wordt afgebroken bij de marges van TextFrame. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

Waar als tekst wordt afgebroken bij de marges van TextFrame. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> The following sample code shows how to wrap text in Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setWrapText(NullableBool.True);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Retourneert of stelt verticale ankertekst in een TextFrame in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retourneert:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Retourneert of stelt verticale ankertekst in een TextFrame in. Lezen/Schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Als NullableBool.True, dan moet de tekst horizontaal gecentreerd zijn in het vak. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retourneert:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Als NullableBool.True, dan moet de tekst horizontaal gecentreerd zijn in het vak. Lezen/Schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Bepaalt de tekstoriëntatie. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en de aangepaste hoek in eigenschap RotationAngle. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retourneert:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Bepaalt de tekstoriëntatie. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en de aangepaste hoek in eigenschap RotationAngle. Lezen/Schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Retourneert of stelt de autofit-modus van de tekst in. Lezen/Schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Retourneert of stelt de autofit-modus van de tekst in. Lezen/Schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> The following sample code shows how to resize shape to Fit Text in a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Shape);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following sample code shows how to shrink text on overflow.
>  
>  Presentation pres = new Presentation();
>  try {
>      ISlide slide = pres.getSlides().get_Item(0);
>      IAutoShape autoShape = slide.getShapes().addAutoShape(ShapeType.Rectangle, 30, 30, 350, 100);
>      Portion portion = new Portion("lorem ipsum...");
>      portion.getPortionFormat().getFillFormat().getSolidFillColor().setColor(Color.BLACK);
>      portion.getPortionFormat().getFillFormat().setFillType(FillType.Solid);
>      autoShape.getTextFrame().getParagraphs().get_Item(0).getPortions().add(portion);
>      ITextFrameFormat textFrameFormat = autoShape.getTextFrame().getTextFrameFormat();
>      textFrameFormat.setAutofitType(TextAutofitType.Normal);
>      pres.save("Output-presentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Retourneert of stelt het aantal kolommen in het tekstergebied in. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent ongedefinieerde waarde. Lezen/Schrijven int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourneert:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Retourneert of stelt het aantal kolommen in het tekstergebied in. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Waarde 0 betekent ongedefinieerde waarde. Lezen/Schrijven int.

--------------------

> ```
> The following sample code shows how to add column in Text frame inside a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation();
>  try {
>      IAutoShape shape1 = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 100, 100, 300, 300);
>      TextFrameFormat format = (TextFrameFormat)shape1.getTextFrame().getTextFrameFormat();
>      format.setColumnCount(2);
>      format.setColumnSpacing(20);
>      shape1.getTextFrame().setText("All these columns are forced to stay within a single text container -- " +
>      "you can add or delete text - and the new or remaining text automatically adjusts " +
>      "itself to stay within the container. You cannot have text spill over from one container " +
>      "to other, though -- because PowerPoint's column options for text are limited!");
>      pres.save("Columns_output.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Retourneert of stelt de ruimte tussen tekstkolommen in het tekstergebied in (in punten). Dit geldt alleen wanneer er meer dan één kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Lezen/Schrijven double.

**Retourneert:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Retourneert of stelt de ruimte tussen tekstkolommen in het tekstergebied in (in punten). Dit geldt alleen wanneer er meer dan één kolom aanwezig is. Deze waarde moet een positief getal zijn. Anders wordt de waarde op nul gezet. Lezen/Schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Specificeert een aangepaste rotatie die op de tekst binnen de begrenzende doos wordt toegepast. Als deze niet gespecificeerd is, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel gespecificeerd is, wordt deze onafhankelijk van de vorm toegepast. De vorm kan een rotatie hebben naast de tekstrotatie. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in eigenschap TextVerticalType. Lezen/Schrijven float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Retourneert:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Specificeert een aangepaste rotatie die op de tekst binnen de begrenzende doos wordt toegepast. Als deze niet gespecificeerd is, wordt de rotatie van de bijbehorende vorm gebruikt. Als deze wel gespecificeerd is, wordt deze onafhankelijk van de vorm toegepast. De vorm kan een rotatie hebben naast de tekstrotatie. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in eigenschap TextVerticalType. Lezen/Schrijven float.

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
public final byte getTransform()
```

Haalt op of stelt de tekstomslagvorm in. Lezen/Schrijven [TextShapeType](../../com.aspose.slides/textshapetype).

**Retourneert:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Haalt op of stelt de tekstomslagvorm in. Lezen/Schrijven [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Haalt op of stelt in dat de tekst plat blijft zelfs als een 3D-rotatie-effect is toegepast. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Haalt op of stelt in dat de tekst plat blijft zelfs als een 3D-rotatie-effect is toegepast. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Haalt de effectieve tekstframe-opmaakgegevens op met de aangebrachte overerving.

--------------------

> ```
> This example demonstrates getting some of effective text frame formatting properties.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try
>  {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      ITextFrameFormatEffectiveData effectiveTextFrameFormat = shape.getTextFrame().getTextFrameFormat().getEffective();
>     
>      System.out.println("Anchoring type: " + effectiveTextFrameFormat.getAnchoringType());
>      System.out.println("Autofit type: " + effectiveTextFrameFormat.getAutofitType());
>      System.out.println("Text vertical type: " + effectiveTextFrameFormat.getTextVerticalType());
>      System.out.println("Margins");
>      System.out.println("   Left: " + effectiveTextFrameFormat.getMarginLeft());
>      System.out.println("   Top: " + effectiveTextFrameFormat.getMarginTop());
>      System.out.println("   Right: " + effectiveTextFrameFormat.getMarginRight());
>      System.out.println("   Bottom: " + effectiveTextFrameFormat.getMarginBottom());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Retourneert:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).