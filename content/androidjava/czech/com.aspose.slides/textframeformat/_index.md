---
title: TextFrameFormat
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Obsahuje vlastnosti formatTextFrameFormatting TextFrames.
type: docs
url: /cs/com.aspose.slides/textframeformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Obsahuje vlastnosti formatTextFrameFormatting objektu TextFrame.

## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Inicializuje novou instanci třídy [TextFrameFormat](../../com.aspose.slides/textframeformat). |

## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Vrací styl textu. |
| [getThreeDFormat()](#getThreeDFormat--) | Vrací objekt ThreeDFormat, který představuje vlastnosti 3D efektů pro text. |
| [getMarginLeft()](#getMarginLeft--) | Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. |
| [getMarginRight()](#getMarginRight--) | Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. |
| [getMarginTop()](#getMarginTop--) | Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. |
| [getWrapText()](#getWrapText--) | True, pokud je text zalomen na okrajích TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True, pokud je text zalomen na okrajích TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. |
| [getCenterText()](#getCenterText--) | Pokud NullableBool.True, text by měl být vodorovně vycentrován v rámečku. |
| [setCenterText(byte value)](#setCenterText-byte-) | Pokud NullableBool.True, text by měl být vodorovně vycentrován v rámečku. |
| [getTextVerticalType()](#getTextVerticalType--) | Určuje orientaci textu. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Určuje orientaci textu. |
| [getAutofitType()](#getAutofitType--) | Vrací nebo nastavuje režim automatického přizpůsobení textu. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Vrací nebo nastavuje režim automatického přizpůsobení textu. |
| [getColumnCount()](#getColumnCount--) | Vrací nebo nastavuje počet sloupců v oblasti textu. |
| [setColumnCount(int value)](#setColumnCount-int-) | Vrací nebo nastavuje počet sloupců v oblasti textu. |
| [getColumnSpacing()](#getColumnSpacing--) | Vrací nebo nastavuje prostor mezi sloupci textu v oblasti textu (v bodech). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Vrací nebo nastavuje prostor mezi sloupci textu v oblasti textu (v bodech). |
| [getRotationAngle()](#getRotationAngle--) | Určuje vlastní rotaci aplikovanou na text v ohraničujícím rámečku. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Určuje vlastní rotaci aplikovanou na text v ohraničujícím rámečku. |
| [getTransform()](#getTransform--) | Získá nebo nastaví tvar zalamování textu. |
| [setTransform(byte value)](#setTransform-byte-) | Získá nebo nastaví tvar zalamování textu. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Získá nebo nastaví zachování plochého textu i po aplikaci 3D rotačního efektu. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Získá nebo nastaví zachování plochého textu i po aplikaci 3D rotačního efektu. |
| [getEffective()](#getEffective--) | Získá efektivní data formátování textového rámce s aplikovaným děděním. |

### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```

Inicializuje novou instanci třídy [TextFrameFormat](../../com.aspose.slides/textframeformat).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze ke čtení long.

**Vrací:**
long

### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Vrací styl textu. Pouze ke čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Vrací objekt ThreeDFormat, který představuje vlastnosti 3D efektů pro text. Pouze ke čtení [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Nastavit transformaci textu
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Nastavit extruzi
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Nastavit obrys
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Nastavit hloubku
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Nastavit materiál
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Nastavit osvětlení
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Nastavit typ kamery
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Vrací:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Vrací:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Vrací:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Vrací:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Vrací:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

True, pokud je text zalomen na okrajích TextFrame. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

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


**Vrací:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```

True, pokud je text zalomen na okrajích TextFrame. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Čtení/Zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Čtení/Zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Pokud NullableBool.True, text by měl být vodorovně vycentrován v rámečku. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Pokud NullableBool.True, text by měl být vodorovně vycentrován v rámečku. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je součtem této vlastnosti a úhlu v vlastnosti RotationAngle. Čtení/Zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Vrací:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je součtem této vlastnosti a úhlu v vlastnosti RotationAngle. Čtení/Zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Čtení/Zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

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


**Vrací:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Čtení/Zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```

Vrací nebo nastavuje počet sloupců v oblasti textu. Tato hodnota musí být kladné číslo; jinak bude nastavena na nulu. Hodnota 0 značí nedefinovanou hodnotu. Čtení/Zápis int.

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


**Vrací:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```

Vrací nebo nastavuje počet sloupců v oblasti textu. Tato hodnota musí být kladné číslo; jinak bude nastavena na nulu. Hodnota 0 značí nedefinovanou hodnotu. Čtení/Zápis int.

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


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```

Vrací nebo nastavuje prostor mezi sloupci textu v oblasti textu (v bodech). Toto platí jen při více než jednom sloupci. Hodnota musí být kladné číslo; jinak bude nastavena na nulu. Čtení/Zápis double.

**Vrací:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Vrací nebo nastavuje prostor mezi sloupci textu v oblasti textu (v bodech). Toto platí jen při více než jednom sloupci. Hodnota musí být kladné číslo; jinak bude nastavena na nulu. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Určuje vlastní rotaci aplikovanou na text v ohraničujícím rámečku. Pokud není specifikována, použije se rotace přidruženého tvaru. Pokud je specifikována, je aplikována nezávisle na tvaru. To znamená, že tvar může mít rotaci navíc k rotaci samotného textu. Výsledná hodnota vizuální rotace textu je součtem této vlastnosti a předdefinovaného vertikálního typu v vlastnosti TextVerticalType. Čtení/Zápis float.

--------------------

> ```
> Zvažte případ, kdy je na tvar aplikována rotace o 90 stupňů ve směru hodinových ručiček. 
>  K tomu má samotné tělo textu rotaci -90 stupňů 
>  proti směru hodinových ručiček aplikovanou. Pak by výsledný tvar vypadal jako
>  otáčený, ale text uvnitř by se jevil, jako by vůbec nebyl otočen.
```

**Vrací:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Určuje vlastní rotaci aplikovanou na text v ohraničujícím rámečku. Pokud není specifikována, použije se rotace přidruženého tvaru. Pokud je specifikována, je aplikována nezávisle na tvaru. To znamená, že tvar může mít rotaci navíc k rotaci samotného textu. Výsledná hodnota vizuální rotace textu je součtem této vlastnosti a předdefinovaného vertikálního typu v vlastnosti TextVerticalType. Čtení/Zápis float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Získá nebo nastaví tvar zalamování textu. Čtení/Zápis [TextShapeType](../../com.aspose.slides/textshapetype).

**Vrací:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Získá nebo nastaví tvar zalamování textu. Čtení/Zápis [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Získá nebo nastaví zachování plochého textu i po aplikaci 3D rotačního efektu. Čtení/Zápis boolean.

**Vrací:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Získá nebo nastaví zachování plochého textu i po aplikaci 3D rotačního efektu. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```

Získá efektivní data formátování textového rámce s aplikovaným děděním.

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


**Vrací:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).