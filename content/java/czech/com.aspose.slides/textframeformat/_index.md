---
title: TextFrameFormat
second_title: Aspose.Slides pro Java - referenční příručka API
description: Obsahuje vlastnosti formatTextFrameFormatting textových rámců.
type: docs
url: /cs/com.aspose.slides/textframeformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Obsahuje vlastnosti formatTextFrameFormatting textového rámce TextFrame.
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | Inicializuje novou instanci třídy [TextFrameFormat](../../com.aspose.slides/textframeformat). |
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Vrací styl textu. |
| [getThreeDFormat()](#getThreeDFormat--) | Vrací objekt ThreeDFormat, který představuje vlastnosti 3d efektu pro text. |
| [getMarginLeft()](#getMarginLeft--) | Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. |
| [getMarginRight()](#getMarginRight--) | Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. |
| [getMarginTop()](#getMarginTop--) | Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. |
| [getWrapText()](#getWrapText--) | True, pokud je text zalamován na okrajích TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True, pokud je text zalamován na okrajích TextFrame. |
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
| [getColumnSpacing()](#getColumnSpacing--) | Vrací nebo nastavuje mezeru mezi sloupci textu v oblasti textu (v bodech). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Vrací nebo nastavuje mezeru mezi sloupci textu v oblasti textu (v bodech). |
| [getRotationAngle()](#getRotationAngle--) | Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. |
| [getTransform()](#getTransform--) | Získá nebo nastaví tvar zalamování textu. |
| [setTransform(byte value)](#setTransform-byte-) | Získá nebo nastaví tvar zalamování textu. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Získá nebo nastaví zachování textu plochého, i když byl použit 3-D Rotation effect. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Získá nebo nastaví zachování textu plochého, i když byl použit 3-D Rotation effect. |
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

Verze. Pouze pro čtení long.

**Vrací:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```

Vrací styl textu. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```

Vrací objekt ThreeDFormat, který představuje vlastnosti 3d efektu pro text. Pouze pro čtení [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Čtení/zápis double.

**Vrací:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Čtení/zápis double.

**Vrací:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Čtení/zápis double.

**Vrací:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```

Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. Čtení/zápis double.

**Vrací:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```

Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```

True, pokud je text zalamován na okrajích TextFrame. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> Následující ukázkový kód ukazuje, jak zalamovat text v Presentation.
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

True, pokud je text zalamován na okrajích TextFrame. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

--------------------

> ```
> Následující ukázkový kód ukazuje, jak zalamovat text v Presentation.
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

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Čtení/zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Čtení/zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```

Pokud NullableBool.True, text by měl být vodorovně vycentrován v rámečku. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```

Pokud NullableBool.True, text by měl být vodorovně vycentrován v rámečku. Čtení/zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```

Určuje orientaci textu. Výsledná hodnota vizuálního otáčení textu je shrnutá z této vlastnosti a vlastního úhlu ve vlastnosti RotationAngle. Čtení/zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Vrací:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```

Určuje orientaci textu. Výsledná hodnota vizuálního otáčení textu je shrnutá z této vlastnosti a vlastního úhlu ve vlastnosti RotationAngle. Čtení/zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Čtení/zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> Následující ukázkový kód ukazuje, jak změnit velikost tvaru, aby se přizpůsobil textu v prezentaci PowerPoint.
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
>  Následující ukázkový kód ukazuje, jak zmenšit text při přeplnění.
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

Vrací nebo nastavuje režim automatického přizpůsobení textu. Čtení/zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

--------------------

> ```
> Následující ukázkový kód ukazuje, jak změnit velikost tvaru, aby se přizpůsobil textu v prezentaci PowerPoint.
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
>  Následující ukázkový kód ukazuje, jak zmenšit text při přeplnění.
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

Vrací nebo nastavuje počet sloupců v oblasti textu. Tato hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/zápis int.

--------------------

> ```
> Následující ukázkový kód ukazuje, jak přidat sloupec do textového rámce v prezentaci PowerPoint.
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

Vrací nebo nastavuje počet sloupců v oblasti textu. Tato hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/zápis int.

--------------------

> ```
> Následující ukázkový kód ukazuje, jak přidat sloupec do textového rámce v prezentaci PowerPoint.
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

Vrací nebo nastavuje mezeru mezi sloupci textu v oblasti textu (v bodech). Toto by se mělo použít jen při více než jednom sloupci. Hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu. Čtení/zápis double.

**Vrací:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```

Vrací nebo nastavuje mezeru mezi sloupci textu v oblasti textu (v bodech). Toto by se mělo použít jen při více než jednom sloupci. Hodnota musí být kladné číslo. Jinak bude hodnota nastavena na nulu. Čtení/zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```

Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. Pokud není zadáno, použije se otočení přidruženého tvaru. Pokud je zadáno, je aplikováno nezávisle na tvaru. To znamená, že tvar může mít otočení aplikované navíc k otočení samotného textu. Výsledná hodnota vizuálního otáčení textu je shrnutá z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Čtení/zápis float.

--------------------

> ```
> Zvažte případ, kdy má tvar aplikovanou rotaci 90 stupňů po směru hodinových ručiček. 
>  K tomu má samotné tělo textu rotaci -90 stupňů 
>  proti směru hodinových ručiček. Pak by výsledný tvar vypadal, že
>  je otočen, ale text uvnitř by se zdál, že vůbec nebyl otočen.
```

**Vrací:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```

Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. Pokud není zadáno, použije se otočení přidruženého tvaru. Pokud je zadáno, je aplikováno nezávisle na tvaru. To znamená, že tvar může mít otočení aplikované navíc k otočení samotného textu. Výsledná hodnota vizuálního otáčení textu je shrnutá z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Čtení/zápis float.

--------------------

> ```
> Zvažte případ, kdy má tvar aplikovanou rotaci 90 stupňů po směru hodinových ručiček. 
>  K tomu má samotné tělo textu rotaci -90 stupňů 
>  proti směru hodinových ručiček. Pak by výsledný tvar vypadal, 
>  že je otočen, ale text uvnitř by se zdál, že vůbec nebyl otočen.
```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```

Získá nebo nastaví tvar zalamování textu. Čtení/zápis [TextShapeType](../../com.aspose.slides/textshapetype).

**Vrací:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```

Získá nebo nastaví tvar zalamování textu. Čtení/zápis [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```

Získá nebo nastaví zachování textu plochého, i když byl použit 3-D Rotation effect. Čtení/zápis boolean.

**Vrací:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```

Získá nebo nastaví zachování textu plochého, i když byl použit 3-D Rotation effect. Čtení/zápis boolean.

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
> Tento příklad ukazuje, jak získat některé z efektivních vlastností formátování textového rámce.
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