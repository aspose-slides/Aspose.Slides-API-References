---
title: TextFrameFormat
second_title: Aspose.Slides for Java API referencia
description: Tartalmazza a TextFrames formatTextFrameFormatting tulajdonságait.
type: docs
url: /hu/com.aspose.slides/textframeformat/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**
[com.aspose.slides.ITextFrameFormat](../../com.aspose.slides/itextframeformat), [com.aspose.slides.IChartTextBlockFormat](../../com.aspose.slides/icharttextblockformat)
```
public final class TextFrameFormat extends PVIObject implements ITextFrameFormat, IChartTextBlockFormat
```

Tartalmazza a TextFrame formatTextFrameFormatting tulajdonságait.
## Konstruktorok

| Konstruktor | Leírás |
| --- | --- |
| [TextFrameFormat()](#TextFrameFormat--) | [TextFrameFormat](../../com.aspose.slides/textframeformat) osztály új példányának inicializálása. |
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getTextStyle()](#getTextStyle--) | Visszaadja a szöveg stílusát. |
| [getThreeDFormat()](#getThreeDFormat--) | Visszaadja a ThreeDFormat objektumot, amely a szöveg 3D hatás tulajdonságait képviseli. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja vagy beállítja a bal margót (pont) egy TextFrame-ben. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Visszaadja vagy beállítja a bal margót (pont) egy TextFrame-ben. |
| [getMarginRight()](#getMarginRight--) | Visszaadja vagy beállítja a jobb margót (pont) egy TextFrame-ben. |
| [setMarginRight(double value)](#setMarginRight-double-) | Visszaadja vagy beállítja a jobb margót (pont) egy TextFrame-ben. |
| [getMarginTop()](#getMarginTop--) | Visszaadja vagy beállítja a felső margót (pont) egy TextFrame-ben. |
| [setMarginTop(double value)](#setMarginTop-double-) | Visszaadja vagy beállítja a felső margót (pont) egy TextFrame-ben. |
| [getMarginBottom()](#getMarginBottom--) | Visszaadja vagy beállítja az alsó margót (pont) egy TextFrame-ben. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Visszaadja vagy beállítja az alsó margót (pont) egy TextFrame-ben. |
| [getWrapText()](#getWrapText--) | Igaz, ha a szöveg a TextFrame margóinál van törve. |
| [setWrapText(byte value)](#setWrapText-byte-) | Igaz, ha a szöveg a TextFrame margóinál van törve. |
| [getAnchoringType()](#getAnchoringType--) | Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. |
| [getCenterText()](#getCenterText--) | Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a dobozban. |
| [setCenterText(byte value)](#setCenterText-byte-) | Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a dobozban. |
| [getTextVerticalType()](#getTextVerticalType--) | Meghatározza a szöveg tájolását. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Meghatározza a szöveg tájolását. |
| [getAutofitType()](#getAutofitType--) | Visszaadja vagy beállítja a szöveg autofit módját. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Visszaadja vagy beállítja a szöveg autofit módját. |
| [getColumnCount()](#getColumnCount--) | Visszaadja vagy beállítja az oszlopok számát a szövegterületen. |
| [setColumnCount(int value)](#setColumnCount-int-) | Visszaadja vagy beállítja az oszlopok számát a szövegterületen. |
| [getColumnSpacing()](#getColumnSpacing--) | Visszaadja vagy beállítja a szövegoszlopok közötti távolságot a szövegterületen (pontban). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Visszaadja vagy beállítja a szövegoszlopok közötti távolságot a szövegterületen (pontban). |
| [getRotationAngle()](#getRotationAngle--) | Megadja a szövegre a körülhatároló keretben alkalmazott egyéni forgatást. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Megadja a szövegre a körülhatároló keretben alkalmazott egyéni forgatást. |
| [getTransform()](#getTransform--) | Lekérdezi vagy beállítja a szöveg becsomagolás alakját. |
| [setTransform(byte value)](#setTransform-byte-) | Lekérdezi vagy beállítja a szöveg becsomagolás alakját. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Lekérdezi vagy beállítja, hogy a szöveg sík maradjon akkor is, ha 3D forgatás hatása alkalmazva lett. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Lekérdezi vagy beállítja, hogy a szöveg sík maradjon akkor is, ha 3D forgatás hatása alkalmazva lett. |
| [getEffective()](#getEffective--) | Lekérdezi a hatékony text frame formázási adatokat az öröklődés alkalmazásával. |
### TextFrameFormat() {#TextFrameFormat--}
```
public TextFrameFormat()
```


[TextFrameFormat](../../com.aspose.slides/textframeformat) osztály új példányának inicializálása.

### getVersion() {#getVersion--}
```
public long getVersion()
```


Verzió. Csak olvasható long.

**Visszatér:**
long
### getTextStyle() {#getTextStyle--}
```
public final ITextStyle getTextStyle()
```


Visszaadja a szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getThreeDFormat() {#getThreeDFormat--}
```
public final IThreeDFormat getThreeDFormat()
```


Visszaadja a ThreeDFormat objektumot, amely a szöveg 3D hatás tulajdonságait képviseli. Csak olvasható [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Szöveg transzformáció beállítása
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Extrúzió beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Kontúr beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Mélység beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Anyag beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Világítás beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Kamera típus beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)
### getMarginLeft() {#getMarginLeft--}
```
public final double getMarginLeft()
```


Visszaadja vagy beállítja a bal margót (pont) egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public final void setMarginLeft(double value)
```


Visszaadja vagy beállítja a bal margót (pont) egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public final double getMarginRight()
```


Visszaadja vagy beállítja a jobb margót (pont) egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public final void setMarginRight(double value)
```


Visszaadja vagy beállítja a jobb margót (pont) egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public final double getMarginTop()
```


Visszaadja vagy beállítja a felső margót (pont) egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public final void setMarginTop(double value)
```


Visszaadja vagy beállítja a felső margót (pont) egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public final double getMarginBottom()
```


Visszaadja vagy beállítja az alsó margót (pont) egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public final void setMarginBottom(double value)
```


Visszaadja vagy beállítja az alsó margót (pont) egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public final byte getWrapText()
```


Igaz, ha a szöveg a TextFrame margóinál van törve. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

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


**Visszatér:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public final void setWrapText(byte value)
```


Igaz, ha a szöveg a TextFrame margóinál van törve. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public final byte getAnchoringType()
```


Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. Olvasás/írás [TextAnchorType](../../com.aspose.slides/textanchortype).

**Visszatér:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public final void setAnchoringType(byte value)
```


Visszaadja vagy beállítja a függőleges rögzítő szöveget egy TextFrame-ben. Olvasás/írás [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public final byte getCenterText()
```


Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a dobozban. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public final void setCenterText(byte value)
```


Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a dobozban. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public final byte getTextVerticalType()
```


Meghatározza a szöveg tájolását. A vizuális szövegforgatásból származó értéket a tulajdonság és a RotationAngle egyéni szöge összegzi. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Visszatér:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public final void setTextVerticalType(byte value)
```


Meghatározza a szöveg tájolását. A vizuális szövegforgatásból származó értéket a tulajdonság és a RotationAngle egyéni szöge összegzi. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public final byte getAutofitType()
```


Visszaadja vagy beállítja a szöveg autofit módját. Olvasás/írás [TextAutofitType](../../com.aspose.slides/textautofittype).

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


**Visszatér:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public final void setAutofitType(byte value)
```


Visszaadja vagy beállítja a szöveg autofit módját. Olvasás/írás [TextAutofitType](../../com.aspose.slides/textautofittype).

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public final int getColumnCount()
```


Visszaadja vagy beállítja az oszlopok számát a szöveg területén. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz állítva. A 0 érték jelentetlen értéket jelent. Olvasás/írás int.

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


**Visszatér:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public final void setColumnCount(int value)
```


Visszaadja vagy beállítja az oszlopok számát a szöveg területén. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz állítva. A 0 érték jelentetlen értéket jelent. Olvasás/írás int.

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


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public final double getColumnSpacing()
```


Visszaadja vagy beállítja a szövegoszlopok közötti távolságot a szövegterületen (pontban). Ez csak akkor alkalmazandó, ha több mint 1 oszlop van jelen. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz állítva. Olvasás/írás double.

**Visszatér:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public final void setColumnSpacing(double value)
```


Visszaadja vagy beállítja a szövegoszlopok közötti távolságot a szövegterületen (pontban). Ez csak akkor alkalmazandó, ha több mint 1 oszlop van jelen. Ennek az értéknek pozitív számnak kell lennie. Ellenkező esetben az érték nullára lesz állítva. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getRotationAngle() {#getRotationAngle--}
```
public final float getRotationAngle()
```


Megadja a szövegre a körülhatároló keretben alkalmazott egyéni forgatást. Ha nincs megadva, akkor a hozzákapcsolt alakzat forgatása kerül használatra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Ez azt jelenti, hogy az alakzat forgatást kaphat, a szöveg mellett, amely szintén saját forgatást kap. A vizuális szövegforgatás értéke a tulajdonság és a TextVerticalType előre definiált függőleges típus alapján kerül összegzésre. Olvasás/írás float.

--------------------

> ```
> Tekintse meg azt az esetet, amikor egy alakzatra 90 fokos óramutató járásával megegyező irányú forgatás van alkalmazva. 
>  Ezen felül a szövegtörzs magára -90 fokos (az óramutató járásával ellentétes) forgatást kap. 
>  az óramutató járásával ellentétes irányban alkalmazva. Ezután a keletkező alakzat úgy jelenik meg, 
>  hogy forgottnak tűnik, de a benne lévő szöveg úgy látszik, mintha egyáltalán nem lenne elforgatva.
```

**Visszatér:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public final void setRotationAngle(float value)
```


Megadja a szövegre a körülhatároló keretben alkalmazott egyéni forgatást. Ha nincs megadva, akkor a hozzákapcsolt alakzat forgatása kerül használatra. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Ez azt jelenti, hogy az alakzat forgatást kaphat, a szöveg mellett, amely szintén saját forgatást kap. A vizuális szövegforgatás értéke a tulajdonság és a TextVerticalType előre definiált függőleges típus alapján kerül összegzésre. Olvasás/írás float.

--------------------

> ```
> Tekintse meg azt az esetet, amikor egy alakzatra 90 fokos óramutató járásával megegyező irányú forgatás van alkalmazva. 
>  Ezen felül a szövegtörzs magára -90 fokos (az óramutató járásával ellentétes) forgatás van alkalmazva. 
>  Ezután a keletkező alakzat forgatottnak tűnik, de a benne lévő szöveg úgy jelenik meg, mintha egyáltalán nem lett volna elforgatva.
```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public final byte getTransform()
```


Visszaadja vagy beállítja a szöveg becsomagolás alakját. Olvasás/írás [TextShapeType](../../com.aspose.slides/textshapetype).

**Visszatér:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public final void setTransform(byte value)
```


Visszaadja vagy beállítja a szöveg becsomagolás alakját. Olvasás/írás [TextShapeType](../../com.aspose.slides/textshapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getKeepTextFlat() {#getKeepTextFlat--}
```
public final boolean getKeepTextFlat()
```


Visszaadja vagy beállítja, hogy a szöveg sík maradjon akkor is, ha 3D forgatás hatását alkalmazták. Olvasás/írás boolean.

**Visszatér:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public final void setKeepTextFlat(boolean value)
```


Visszaadja vagy beállítja, hogy a szöveg sík maradjon akkor is, ha 3D forgatás hatását alkalmazták. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final ITextFrameFormatEffectiveData getEffective()
```


Visszaadja a hatékony text frame formázási adatokat az öröklődés alkalmazásával.

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


**Visszatér:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).