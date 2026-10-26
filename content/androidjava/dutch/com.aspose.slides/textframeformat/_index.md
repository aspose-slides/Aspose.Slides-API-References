---
title: TextFrameFormat
second_title: Aspose.Slides voor Android via Java API-referentie
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

Bevat de formatTextFrameFormatting-eigenschappen van TextFrame.
## Constructors

| Constructor | Beschrijving |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Initialiseert een nieuw exemplaar van de [TextFrameFormat](../../com.aspose.slides/textframeformat) klasse. |
## Methods

| Method | Beschrijving |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Retourneert de stijl van de tekst. |
| [getThreeDFormat()](#getThreeDFormat--) | Retourneert het ThreeDFormat-object dat de 3D-effecteigenschappen voor een tekst vertegenwoordigt. |
| [getMarginLeft()](#getMarginLeft--) | Haalt de linkermarge (punten) op of stelt deze in een TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Haalt de linkermarge (punten) op of stelt deze in een TextFrame. |
| [getMarginRight()](#getMarginRight--) | Haalt de rechtermarge (punten) op of stelt deze in een TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Haalt de rechtermarge (punten) op of stelt deze in een TextFrame. |
| [getMarginTop()](#getMarginTop--) | Haalt de bovenmarge (punten) op of stelt deze in een TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Haalt de bovenmarge (punten) op of stelt deze in een TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Haalt de ondermarge (punten) op of stelt deze in een TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Haalt de ondermarge (punten) op of stelt deze in een TextFrame. |
| [getWrapText()](#getWrapText--) | Waar als tekst wordt afgebroken bij de marges van de TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Waar als tekst wordt afgebroken bij de marges van de TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Haalt de verticale ankertekst op of stelt deze in een TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Haalt de verticale ankertekst op of stelt deze in een TextFrame. |
| [getCenterText()](#getCenterText--) | Als NullableBool.True, dan moet de tekst horizontaal gecentreerd worden in het vak. |
| [setCenterText(byte value)](#setCenterText-byte-) | Als NullableBool.True, dan moet de tekst horizontaal gecentreerd worden in het vak. |
| [getTextVerticalType()](#getTextVerticalType--) | Bepaalt de oriëntatie van de tekst. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bepaalt de oriëntatie van de tekst. |
| [getAutofitType()](#getAutofitType--) | Haalt de autofit-modus van de tekst op of stelt deze in. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Haalt de autofit-modus van de tekst op of stelt deze in. |
| [getColumnCount()](#getColumnCount--) | Haalt het aantal kolommen in het tekstgebied op of stelt dit in. |
| [setColumnCount(int value)](#setColumnCount-int-) | Haalt het aantal kolommen in het tekstgebied op of stelt dit in. |
| [getColumnSpacing()](#getColumnSpacing--) | Haalt de ruimte tussen tekstkolommen in het tekstgebied op (in punten) of stelt deze in. |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Haalt de ruimte tussen tekstkolommen in het tekstgebied op (in punten) of stelt deze in. |
| [getRotationAngle()](#getRotationAngle--) | Specificeert de aangepaste rotatie die op de tekst binnen de omvattende doos wordt toegepast. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specificeert de aangepaste rotatie die op de tekst binnen de omvattende doos wordt toegepast. |
| [getTransform()](#getTransform--) | Haalt de vorm voor tekstomloop op of stelt deze in. |
| [setTransform(byte value)](#setTransform-byte-) | Haalt de vorm voor tekstomloop op of stelt deze in. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Haalt de instelling op of stelt deze in om tekst vlak te houden, zelfs als een 3-D-rotatie-effect is toegepast. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Haalt de instelling op of stelt deze in om tekst vlak te houden, zelfs als een 3-D-rotatie-effect is toegepast. |
| [getEffective()](#getEffective--) | Haalt de effectieve opmaakgegevens van het tekstframe op met de toegepaste overerving. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Initialiseert een nieuw exemplaar van de [TextFrameFormat](../../com.aspose.slides/textframeformat) klasse.

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versie. Alleen-lezen long.

**Retour:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Retourneert de stijl van de tekst. Alleen-lezen [ITextStyle](../../com.aspose.slides/itextstyle).

**Retour:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
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


**Retour:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Haalt de linkermarge (punten) op of stelt deze in een TextFrame. Lezen/schrijven double.

**Retour:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Haalt de linkermarge (punten) op of stelt deze in een TextFrame. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Haalt de rechtermarge (punten) op of stelt deze in een TextFrame. Lezen/schrijven double.

**Retour:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Haalt de rechtermarge (punten) op of stelt deze in een TextFrame. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Haalt de bovenmarge (punten) op of stelt deze in een TextFrame. Lezen/schrijven double.

**Retour:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Haalt de bovenmarge (punten) op of stelt deze in een TextFrame. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Haalt de ondermarge (punten) op of stelt deze in een TextFrame. Lezen/schrijven double.

**Retour:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Haalt de ondermarge (punten) op of stelt deze in een TextFrame. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

Waar als tekst wordt afgebroken bij de marges van de TextFrame. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> De volgende voorbeeldcode toont hoe je tekst in Presentation kunt omwikkelen.
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


**Retour:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

Waar als tekst wordt afgebroken bij de marges van de TextFrame. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> De volgende voorbeeldcode toont hoe je tekst in Presentation kunt omwikkelen.
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

Haalt de verticale ankertekst op of stelt deze in een TextFrame. Lezen/schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retour:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Haalt de verticale ankertekst op of stelt deze in een TextFrame. Lezen/schrijven [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Als NullableBool.True, dan moet de tekst horizontaal gecentreerd worden in het vak. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Als NullableBool.True, dan moet de tekst horizontaal gecentreerd worden in het vak. Lezen/schrijven [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Bepaalt de oriëntatie van de tekst. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en de aangepaste hoek in property RotationAngle. Lezen/schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retour:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Bepaalt de oriëntatie van de tekst. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en de aangepaste hoek in property RotationAngle. Lezen/schrijven [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Haalt de autofit-modus van de tekst op of stelt deze in. Lezen/schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

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

**Retour:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Haalt de autofit-modus van de tekst op of stelt deze in. Lezen/schrijven [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> De volgende voorbeeldcode toont hoe je een vorm kunt aanpassen zodat de tekst erin past in een PowerPoint-presentatie.
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
>  De volgende voorbeeldcode toont hoe je tekst kunt verkleinen bij overflow.
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

Haalt het aantal kolommen in het tekstgebied op of stelt dit in. Deze waarde moet positief zijn; anders wordt de waarde op nul gezet. Waarde 0 betekent ongedefinieerde waarde. Lezen/schrijven int.

--------------------

> ```
> De volgende voorbeeldcode toont hoe je een kolom kunt toevoegen in een tekstvak binnen een PowerPoint-presentatie.
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


**Retour:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Haalt het aantal kolommen in het tekstgebied op of stelt dit in. Deze waarde moet positief zijn; anders wordt de waarde op nul gezet. Waarde 0 betekent ongedefinieerde waarde. Lezen/schrijven int.

--------------------

> ```
> De volgende voorbeeldcode toont hoe je een kolom kunt toevoegen in een tekstvak binnen een PowerPoint-presentatie.
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
>  
>  De volgende voorbeeldcode toont hoe je een kolom kunt toevoegen in een tekstvak binnen een PowerPoint-presentatie.
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

Haalt de ruimte tussen tekstkolommen in het tekstgebied op (in punten) of stelt deze in. Dit is alleen van toepassing wanneer er meer dan één kolom aanwezig is. Deze waarde moet positief zijn; anders wordt de waarde op nul gezet. Lezen/schrijven double.

**Retour:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Haalt de ruimte tussen tekstkolommen in het tekstgebied op (in punten) of stelt deze in. Dit is alleen van toepassing wanneer er meer dan één kolom aanwezig is. Deze waarde moet positief zijn; anders wordt de waarde op nul gezet. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Specificeert de aangepaste rotatie die op de tekst binnen de omvattende doos wordt toegepast. Indien niet gespecificeerd, wordt de rotatie van de bijbehorende vorm gebruikt. Indien gespecificeerd, wordt deze onafhankelijk van de vorm toegepast; de vorm kan een rotatie hebben naast de rotatie van de tekst zelf. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in property TextVerticalType. Lezen/schrijven float.

--------------------

> ```
> Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft toegepast. 
>  Daarnaast heeft het tekstgedeelte zelf een rotatie van -90 graden 
>  tegen de klok in toegepast. Dan zou de resulterende vorm lijken te
>  gedraaid zijn, maar de tekst erin zou lijken alsof deze niet gedraaid was.
```

**Retour:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Specificeert de aangepaste rotatie die op de tekst binnen de omvattende doos wordt toegepast. Indien niet gespecificeerd, wordt de rotatie van de bijbehorende vorm gebruikt. Indien gespecificeerd, wordt deze onafhankelijk van de vorm toegepast; de vorm kan een rotatie hebben naast de rotatie van de tekst zelf. De resulterende visuele rotatiewaarde wordt samengevat uit deze eigenschap en het vooraf gedefinieerde verticale type in property TextVerticalType. Lezen/schrijven float.

--------------------

> ```
> Beschouw het geval waarin een vorm een rotatie van 90 graden met de klok mee heeft toegepast. 
>  Daarnaast heeft het tekstgedeelte zelf een rotatie van -90 graden 
>  tegen de klok in toegepast. Dan zou de resulterende vorm lijken te
>  gedraaid zijn, maar de tekst erin zou lijken alsof deze niet gedraaid was.
```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Haalt de vorm voor tekstomloop op of stelt deze in. Lezen/schrijven [TextShapeType](../../com.aspose.slides/textshapetype).

**Retour:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Haalt de vorm voor tekstomloop op of stelt deze in. Lezen/schrijven [TextShapeType](../../com.aspose.slides/textshapetype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Haalt de instelling op of stelt deze in om tekst vlak te houden, zelfs als een 3-D-rotatie-effect is toegepast. Lezen/schrijven boolean.

**Retour:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Haalt de instelling op of stelt deze in om tekst vlak te houden, zelfs als een 3-D-rotatie-effect is toegepast. Lezen/schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Haalt de effectieve opmaakgegevens van het tekstframe op met de toegepaste overerving.

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

**Retour:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - Een [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).