---
title: TextFrameFormat
second_title: Aspose.Slides för Android via Java API-referens
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

Innehåller TextFrame:s formatTextFrameFormatting-egenskaper.
## Konstruktorer

| Konstruktor | Beskrivning |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Initierar en ny instans av [TextFrameFormat](../../com.aspose.slides/textframeformat) klass. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Returnerar textens stil. |
| [getThreeDFormat()](#getThreeDFormat--) | Returnerar ThreeDFormat-objektet som representerar 3D-effektegenskaper för en text. |
| [getMarginLeft()](#getMarginLeft--) | Returnerar eller sätter den vänstra marginalen (punkter) i en TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returnerar eller sätter den vänstra marginalen (punkter) i en TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returnerar eller sätter den högra marginalen (punkter) i en TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returnerar eller sätter den högra marginalen (punkter) i en TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returnerar eller sätter den övre marginalen (punkter) i en TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returnerar eller sätter den övre marginalen (punkter) i en TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returnerar eller sätter den nedre marginalen (punkter) i en TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returnerar eller sätter den nedre marginalen (punkter) i en TextFrame. |
| [getWrapText()](#getWrapText--) | True om texten radbryts vid TextFrames marginaler. |
| [setWrapText(byte value)](#setWrapText-byte-) | True om texten radbryts vid TextFrames marginaler. |
| [getAnchoringType()](#getAnchoringType--) | Returnerar eller sätter vertikal ankaretext i en TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returnerar eller sätter vertikal ankaretext i en TextFrame. |
| [getCenterText()](#getCenterText--) | Om NullableBool.True så bör texten centreras horisontellt i rutan. |
| [setCenterText(byte value)](#setCenterText-byte-) | Om NullableBool.True så bör texten centreras horisontellt i rutan. |
| [getTextVerticalType()](#getTextVerticalType--) | Bestämmer textens orientering. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Bestämmer textens orientering. |
| [getAutofitType()](#getAutofitType--) | Returnerar eller sätter textens autofit-läge. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returnerar eller sätter textens autofit-läge. |
| [getColumnCount()](#getColumnCount--) | Returnerar eller sätter antalet kolumner i textområdet. |
| [setColumnCount(int value)](#setColumnCount-int-) | Returnerar eller sätter antalet kolumner i textområdet. |
| [getColumnSpacing()](#getColumnSpacing--) | Returnerar eller sätter avståndet mellan textkolumner i textområdet (i punkter). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Returnerar eller sätter avståndet mellan textkolumner i textområdet (i punkter). |
| [getRotationAngle()](#getRotationAngle--) | Specificerar anpassad rotation som appliceras på texten inom begränsningsrutan. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specificerar anpassad rotation som appliceras på texten inom begränsningsrutan. |
| [getTransform()](#getTransform--) | Hämtar eller sätter textomslutningsform. |
| [setTransform(byte value)](#setTransform-byte-) | Hämtar eller sätter textomslutningsform. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Hämtar eller sätter att hålla texten plan även om en 3-D-rotations-effekt tillämpats. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Hämtar eller sätter att hålla texten plan även om en 3-D-rotations-effekt tillämpats. |
| [getEffective()](#getEffective--) | Hämtar effektiv textframe-formateringsdata med arv tillämpat. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


Initierar en ny instans av [TextFrameFormat](../../com.aspose.slides/textframeformat) klass.

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


Returnerar ThreeDFormat-objektet som representerar 3D-effektegenskaper för en text. Skrivskyddad [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Sätt texttransformation
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Sätt extrudering
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Sätt kontur
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Sätt djup
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Sätt material
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Sätt belysning
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Sätt kameratyp
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


True om texten radbryts vid TextFrames marginaler. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> Följande exempel visar hur man radbryter text i Presentation.
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


True om texten radbryts vid TextFrames marginaler. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> Följande exempel visar hur man radbryter text i Presentation.
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


Returnerar eller sätter vertikal ankaretext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Returnerar:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


Returnerar eller sätter vertikal ankaretext i en TextFrame. Läs/skriv [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


Om NullableBool.True så bör texten centreras horisontellt i rutan. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Returnerar:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


Om NullableBool.True så bör texten centreras horisontellt i rutan. Läs/skriv [NullableBool](../../com.aspose.slides/nullablebool).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Bestämmer textens orientering. Det resulterande värdet för visuell textrotation summeras från denna egenskap och den anpassade vinkeln i egenskapen RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Returnerar:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Bestämmer textens orientering. Det resulterande värdet för visuell textrotation summeras från denna egenskap och den anpassade vinkeln i egenskapen RotationAngle. Läs/skriv [TextVerticalType](../../com.aspose.slides/textverticaltype).

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
> Följande exempel visar hur man ändrar storlek på formen för att anpassa text i en PowerPoint-presentation.
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
>  Följande exempel visar hur man krymper text vid överspill.
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
> Följande exempel visar hur man ändrar storlek på formen för att anpassa text i en PowerPoint-presentation.
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
>  Följande exempel visar hur man krymper text vid överspill.
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
> Följande exempel visar hur man lägger till kolumn i Text frame i en PowerPoint-presentation.
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
> Följande exempel visar hur man lägger till kolumn i Text frame i en PowerPoint-presentation.
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


Returnerar eller sätter avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast tillämpas när mer än en kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs/skriv double.

**Returnerar:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


Returnerar eller sätter avståndet mellan textkolumner i textområdet (i punkter). Detta bör endast tillämpas när mer än en kolumn finns. Detta värde måste vara ett positivt tal. Annars sätts värdet till noll. Läs/skriv double.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


Specificerar anpassad rotation som appliceras på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges appliceras den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet för visuell textrotation summeras från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs/skriv float.

--------------------

> ```
> Tänk på fallet där en form har en rotation på 90 grader medurs applicerad på den. 
>  Utöver detta har textkroppen själv en rotation på -90 grader 
>  moturs applicerad på den. Då skulle den resulterande formen verka
>  vara roterad men texten inom den skulle verka som om den inte hade roterats alls.
```

**Returnerar:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


Specificerar anpassad rotation som appliceras på texten inom begränsningsrutan. Om den inte anges används rotationen för den medföljande formen. Om den anges appliceras den oberoende av formen. Det innebär att formen kan ha en rotation utöver att texten själv har en rotation. Det resulterande värdet för visuell textrotation summeras från denna egenskap och den fördefinierade vertikala typen i egenskapen TextVerticalType. Läs/skriv float.

--------------------

> ```
> Tänk dig fallet där en form har en rotation på 90 grader medurs applicerad på den. 
>  Utöver detta har textkroppen själv en rotation på -90 grader 
>  moturs applicerad på den. Då skulle den resulterande formen verka att
>  vara roterad men texten inom den skulle verka som om den inte hade roterats alls.
```

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```


Hämtar eller sätter textomslutningsform. Läs/skriv [TextShapeType](../../com.aspose.slides/textshapetype).

**Returnerar:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```


Hämtar eller sätter textomslutningsform. Läs/skriv [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


Hämtar eller sätter att hålla texten plan även om en 3-D-rotations-effekt tillämpats. Läs/skriv boolean.

**Returnerar:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


Hämtar eller sätter att hålla texten plan även om en 3-D-rotations-effekt tillämpats. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


Hämtar effektiv textframe-formateringsdata med arv tillämpat.

--------------------

> ```
> Detta exempel demonstrerar hur man hämtar några av de effektiva textframe-formateringsegenskaperna.
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