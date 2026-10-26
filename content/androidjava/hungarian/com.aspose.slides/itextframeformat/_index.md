---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Contains the TextFrames formatting properties.
type: docs
url: /hu/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Tartalmazza a TextFrame formázási tulajdonságait.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Visszaadja a szöveg stílusát. |
| [getMarginLeft()](#getMarginLeft--) | Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. |
| [getMarginRight()](#getMarginRight--) | Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. |
| [setMarginRight(double value)](#setMarginRight-double-) | Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. |
| [getMarginTop()](#getMarginTop--) | Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. |
| [setMarginTop(double value)](#setMarginTop-double-) | Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. |
| [getMarginBottom()](#getMarginBottom--) | Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. |
| [getWrapText()](#getWrapText--) | Igaz, ha a szöveg a TextFrame szélein van tördelve. |
| [setWrapText(byte value)](#setWrapText-byte-) | Igaz, ha a szöveg a TextFrame szélein van tördelve. |
| [getAnchoringType()](#getAnchoringType--) | Visszaadja vagy beállítja a függőleges horgonyos szöveget egy TextFrame-ben. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Visszaadja vagy beállítja a függőleges horgonyos szöveget egy TextFrame-ben. |
| [getCenterText()](#getCenterText--) | Ha NullableBool.True, akkor a szöveget vízszintesen kell középre helyezni a keretben. |
| [setCenterText(byte value)](#setCenterText-byte-) | Ha NullableBool.True, akkor a szöveget vízszintesen kell középre helyezni a keretben. |
| [getTextVerticalType()](#getTextVerticalType--) | Meghatározza a szöveg tájolását. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Meghatározza a szöveg tájolását. |
| [getAutofitType()](#getAutofitType--) | Visszaadja vagy beállítja a szöveg autofit módját. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Visszaadja vagy beállítja a szöveg autofit módját. |
| [getColumnCount()](#getColumnCount--) | Visszaadja vagy beállítja az oszlopok számát a szövegterületen. |
| [setColumnCount(int value)](#setColumnCount-int-) | Visszaadja vagy beállítja az oszlopok számát a szövegterületen. |
| [getColumnSpacing()](#getColumnSpacing--) | Visszaadja vagy beállítja a szövegoszlopok közti távolságot a szövegterületen (pontban). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Visszaadja vagy beállítja a szövegoszlopok közti távolságot a szövegterületen (pontban). |
| [getThreeDFormat()](#getThreeDFormat--) | Visszaadja a ThreeDFormat objektumot, amely a szöveg 3D-hatás tulajdonságait képviseli. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Visszaadja vagy állítja be, hogy a szöveg teljesen kívül maradjon a 3D-jelenetből. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Visszaadja vagy állítja be, hogy a szöveg teljesen kívül maradjon a 3D-jelenetből. |
| [getRotationAngle()](#getRotationAngle--) | Megadja az egyéni forgást, amely a szövegre vonatkozik a keretben. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Megadja az egyéni forgást, amely a szövegre vonatkozik a keretben. |
| [getTransform()](#getTransform--) | Lekéri vagy beállítja a szöveg körbefuttatásának alakját. |
| [setTransform(byte value)](#setTransform-byte-) | Lekéri vagy beállítja a szöveg körbefuttatásának alakját. |
| [getEffective()](#getEffective--) | Lekéri a hatékony szövegdoboz formázási adatokat az öröklődés alkalmazásával. |

### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```

Visszaadja a szöveg stílusát. Csak olvasható [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Visszaadja vagy beállítja a bal margót (pontban) egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Visszaadja vagy beállítja a jobb margót (pontban) egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Visszaadja vagy beállítja a felső margót (pontban) egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. Olvasás/írás double.

**Visszatér:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Visszaadja vagy beállítja az alsó margót (pontban) egy TextFrame-ben. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Igaz, ha a szöveg a TextFrame szélein van tördelve. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Igaz, ha a szöveg a TextFrame szélein van tördelve. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Visszaadja vagy beállítja a függőleges horgonyos szöveget egy TextFrame-ben. Olvasás/írás [TextAnchorType](../../com.aspose.slides/textanchortype).

**Visszatér:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Visszaadja vagy beállítja a függőleges horgonyos szöveget egy TextFrame-ben. Olvasás/írás [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Ha NullableBool.True, akkor a szöveget vízszintesen kell középre helyezni a keretben. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Ha NullableBool.True, akkor a szöveget vízszintesen kell középre helyezni a keretben. Olvasás/írás [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Meghatározza a szöveg tájolását. A vizuális szöveg forgatás eredő értéke ebből a tulajdonságból és a RotationAngle egyéni szögből jön. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Visszatér:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Meghatározza a szöveg tájolását. A vizuális szöveg forgatás eredő értéke ebből a tulajdonságból és a RotationAngle egyéni szögből jön. Olvasás/írás [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Visszaadja vagy beállítja a szöveg autofit módját. Olvasás/írás [TextAutofitType](../../com.aspose.slides/textautofittype).

**Visszatér:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Visszaadja vagy beállítja a szöveg autofit módját. Olvasás/írás [TextAutofitType](../../com.aspose.slides/textautofittype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Visszaadja vagy beállítja az oszlopok számát a szövegterületen. Ennek a értéknek pozitív számnak kell lennie; ellenkező esetben nulla lesz. A 0 érték jelentése: nincs meghatározva. Olvasás/írás int.

**Visszatér:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Visszaadja vagy beállítja az oszlopok számát a szövegterületen. Ennek a értéknek pozitív számnak kell lennie; ellenkező esetben nulla lesz. A 0 érték jelentése: nincs meghatározva. Olvasás/írás int.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Visszaadja vagy beállítja a szövegoszlopok közti távolságot a szövegterületen (pontban). Csak akkor alkalmazandó, ha egynél több oszlop van. Ennek az értéknek pozitív számnak kell lennie; ellenkező esetben nulla lesz. Olvasás/írás double.

**Visszatér:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Visszaadja vagy beállítja a szövegoszlopok közti távolságot a szövegterületen (pontban). Csak akkor alkalmazandó, ha egynél több oszlop van. Ennek az értéknek pozitív számnak kell lennie; ellenkező esetben nulla lesz. Olvasás/írás double.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Visszaadja a ThreeDFormat objektumot, amely a szöveg 3D-hatás tulajdonságait képviseli. Csak olvasható [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Set text transformation
>      // Szöveg átalakítás beállítása
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Set Extrusion
>      // Extrudálás beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Set Contour
>      // Kontúr beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Set Depth
>      // Mélység beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Set Material
>      // Anyag beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Set Lighting
>      // Megvilágítás beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Set camera type
>      // Kamera típus beállítása
>      textFrame.getTextFrameFormat().getThreeDFormat().getCamera().setCameraType(CameraPresetType.PerspectiveContrastingRightFacing);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Visszatér:**
[IThreeDFormat](../../com.aspose.slides/ithreedformat)

### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Visszaadja vagy állítja be, hogy a szöveg teljesen kívül maradjon a 3D-jelenetből. Olvasás/írás boolean.

**Visszatér:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Visszaadja vagy állítja be, hogy a szöveg teljesen kívül maradjon a 3D-jelenetből. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Megadja az egyéni forgást, amely a szövegre vonatkozik a keretben. Ha nincs megadva, a kísérő alakzat forgását használja. Ha meg van adva, függetlenül az alakzattól alkalmazzák. A vizuális szöveg forgatás eredő értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából származik. Olvasás/írás float.

--------------------

> ```
> Tekintsd meg azt az esetet, amikor egy alakzatra 90 fokos óramutató járásával megegyező forgatás van alkalmazva. 
>  Ezen felül a szövegtörzsnek -90 fokos, óramutatóval ellentétes forgatása van 
>  óramutatóval ellentétes irányban alkalmazva. Ezután a keletkezett alakzat úgy tűnik, hogy
>  el van forgatva, de a benne lévő szöveg úgy tűnik, mintha egyáltalán nem lett volna elforgatva.
> ```

**Visszatér:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Megadja az egyéni forgást, amely a szövegre vonatkozik a keretben. Ha nincs megadva, a kísérő alakzat forgását használja. Ha meg van adva, függetlenül az alakzattól alkalmazzák. A vizuális szöveg forgatás eredő értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából származik. Olvasás/írás float.

--------------------

> ```
> Tekintsd meg azt az esetet, amikor egy alakzatra 90 fokos óramutató járásával megegyező forgatás van alkalmazva. 
>  Ezen felül a szövegtörzsnek -90 fokos óramutatóval ellentétes forgatása van 
>  alkalmazva. Ezután a keletkezett alakzat úgy tűnik, hogy
>  el van forgatva, de a benne lévő szöveg úgy tűnik, mintha egyáltalán nem lett volna elforgatva.
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Lekéri vagy beállítja a szöveg körbefuttatásának alakját. Olvasás/írás [TextShapeType](../../com.aspose.slides/textshapetype).

**Visszatér:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Lekéri vagy beállítja a szöveg körbefuttatásának alakját. Olvasás/írás [TextShapeType](../../com.aspose.slides/textshapetype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Lekéri a hatékony szövegdoboz formázási adatokat az öröklődés alkalmazásával.

**Visszatér:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).