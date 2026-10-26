---
title: TextFrameFormat
second_title: Aspose.Slides för Java API-referens
description: Innehåller TextFrames formatTextFrameFormatting egenskaper.
type: docs
url: /sv/com.aspose.slides/textframeformat/
---
**Arv:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Alla implementerade gränssnitt:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Innehåller TextFrames formatTextFrameFormatting-egenskaper.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Initierar en ny instans av klass [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Returnerar textens stil. |
| [getThreeDFormat()](#getThreeDFormat--) | Returnerar ThreeDFormat-objektet som representerar 3d-effektegenskaper för en text. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller sätter den vänstra marginalen (punkter) i en TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returnerar eller sätter den vänstra marginalen (punkter) i en TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller sätter den högra marginalen (punkter) i en TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returnerar eller sätter den högra marginalen (punkter) i en TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returnerar eller sätter den övre marginalen (punkter) i en TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returnerar eller sätter den övre marginalen (punkter) i en TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returnerar eller sätter den nedre marginalen (punkter) i en TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returnerar eller sätter den nedre marginalen (punkter) i en TextFrame. |
| [getWrapText()](#getWrapText--) | Sant om texten är omsluten vid TextFrames marginaler. |
| [setWrapText(byte value)](#setWrapText-byte-) | Sant om texten är omsluten vid TextFrames marginaler. |
| [getAnchoringType()](#getAnchoringType--) | Returnerar eller sätter vertikal ankartext i en TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returnerar eller sätter vertikal ankartext i en TextFrame. |
| [getCenterText()](#getCenterText--) | Om NullableBool.True ska texten centreras horisontellt i boxen. |
| [setCenterText(byte value)](#setCenterText-byte-) | Om NullableBool.True ska texten centreras horisontellt i boxen. |
| [getTextVerticalType()](#getTextVerticalType--) | Bestämmer textriktning. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bestämmer textriktning. |
| [getAutofitType()](#getAutofitType--) | Returnerar eller sätter textens autofit-läge. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returnerar eller sätter textens autofit-läge. |
| [getColumnCount()](#getColumnCount--) | Returnerar eller sätter antalet kolumner i textområdet. |
| [setColumnCount(int value)](#setColumnCount-int-) | Returnerar eller sätter antalet kolumner i textområdet. |
| [getColumnSpacing()](#getColumnSpacing--) | Returnerar eller sätter avståndet mellan textkolumner i textområdet (i punkter). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Returnerar eller sätter avståndet mellan textkolumner i textområdet (i punkter). |
| [getRotationAngle()](#getRotationAngle--) | Specificerar anpassad rotation som tillämpas på texten inom den omgivande rutan. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specificerar anpassad rotation som tillämpas på texten inom den omgivande rutan. |
| [getTransform()](#getTransform--) | Hämtar eller sätter textomslagningsform. |
| [setTransform(byte value)](#setTransform-byte-) | Hämtar eller sätter textomslagningsform. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Hämtar eller sätter att hålla texten platt även om en 3-D-rotations-effekt har tillämpats. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Hämtar eller sätter att hålla texten platt även om en 3-D-rotations-effekt har tillämpats. |
| [getEffective()](#getEffective--) | Hämtar effektiv formateringsdata för textramen med arv tillämpat. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Initierar en ny instans av klass [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Version. Skrivskyddad long.

**Returnerar:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Returnerar textens stil. Skrivskyddad [ITextStyle](../../com.aspose.slides/itextstyle).

**Returnerar:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
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
>      // Ställ in ljussättning
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
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Returnerar eller sätter den vänstra marginalen (punkter) i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Returnerar eller sätter den vänstra marginalen (punkter) i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Returnerar eller sätter den högra marginalen (punkter) i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Returnerar eller sätter den högra marginalen (punkter) i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Returnerar eller sätter den övre marginalen (punkter) i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Returnerar eller sätter den övre marginalen (punkter) i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Returnerar eller sätter den nedre marginalen (punkter) i en TextFrame. Läs/skriv double.

**Returnerar:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Returnerar eller sätter den nedre marginalen (punkter) i en TextFrame. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

Sant om texten är omsluten vid TextFrames marginaler. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

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


**Returnerar:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

Sant om texten är omsluten vid TextFrames marginaler. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Returnerar eller sätter vertikal ankartext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returnerar:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Returnerar eller sätter vertikal ankartext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Om NullableBool.True ska texten centreras horisontellt i boxen. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Om NullableBool.True ska texten centreras horisontellt i boxen. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Bestämmer textriktning. Det resulterande värdet av visuell textrotation sammanställt från denna egenskap och anpassad vinkel i egenskapen RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returnerar:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Bestämmer textriktning. Det resulterande värdet av visuell textrotation sammanställt från denna egenskap och anpassad vinkel i egenskapen RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Returnerar eller sätter textens autofit-läge. Läs/skriv [TextAutofitType](../../com.aspose.slides/textautofittype).

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


**Returnerar:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Returnerar eller sätter textens autofit-läge. Läs/skriv [TextAutofitType](../../com.aspose.slides/textautofittype).

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Returnerar eller sätter antalet kolumner i textområdet. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Värde 0 betyder odefinierat värde. Läs/skriv int.

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

**Returnerar:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Returnerar eller sätter antalet kolumner i textområdet. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Värde 0 betyder odefinierat värde. Läs/skriv int.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Returnerar eller sätter avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast tillämpas när mer än 1 kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs/skriv double.

**Returnerar:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Returnerar eller sätter avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast tillämpas när mer än 1 kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Specificerar anpassad rotation som tillämpas på texten inom den omgivande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation sammanställt från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Läs/skriv float.

--------------------

> ```
> Betrakta fallet där en form har en rotation på 90 grader medurs tillämpad på den. 
>  Utöver detta har själva textkroppen en rotation på -90 grader 
>  moturs tillämpad på den. Då skulle den resulterande formen verka
>  roterad men texten i den skulle framstå som om den inte hade roterats alls.
```

**Returnerar:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Specificerar anpassad rotation som tillämpas på texten inom den omgivande rutan. Om den inte anges används rotationen för den medföljande formen. Om den anges tillämpas den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet av visuell textrotation sammanställt från denna egenskap och fördefinierad vertikal typ i egenskapen TextVerticalType. Läs/skriv float.

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
public final byte getTransform()
```

Hämtar eller sätter textomslagningsform. Läs/skriv [TextShapeType](../../com.aspose.slides/textshapetype).

**Returnerar:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public                          
```

Hämtar eller sätter textomslagningsform. Läs/skriv [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Hämtar eller sätter att hålla texten platt även om en 3-D-rotations-effekt har tillämpats. Läs/skriv boolean.

**Returnerar:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Hämtar eller sätter att hålla texten platt även om en 3-D-rotations-effekt har tillämpats. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Hämtar effektiv formateringsdata för textramen med arv tillämpat.

--------------------

> ```
> Detta exempel demonstrerar hur man får några av de effektiva formateringsegenskaperna för textramen.
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


**Returnerar:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).