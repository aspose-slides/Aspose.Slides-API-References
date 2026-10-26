---
title: ITextFrameFormat
second_title: Aspose.Slides for Java API Referencia
description: Tartalmazza a TextFrame formázási tulajdonságait.
type: docs
url: /hu/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Tartalmazza a TextFrame formázási tulajdonságait.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Returns text's style. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin (points) in a TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returns or sets the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin (points) in a TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returns or sets the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns or sets the top margin (points) in a TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returns or sets the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns or sets the bottom margin (points) in a TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returns or sets the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | True if text is wrapped at TextFrame's margins. |
| [setWrapText(byte value)](#setWrapText-byte-) | True if text is wrapped at TextFrame's margins. |
| [getAnchoringType()](#getAnchoringType--) | Returns or sets vertical anchor text in a TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returns or sets vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | If NullableBool.True then text should be centered in box horizontally. |
| [setCenterText(byte value)](#setCenterText-byte-) | If NullableBool.True then text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Determines text orientation. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determines text orientation. |
| [getAutofitType()](#getAutofitType--) | Returns or sets text's autofit mode. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returns or sets text's autofit mode. |
| [getColumnCount()](#getColumnCount--) | Returns or sets number of columns in the text area. |
| [setColumnCount(int value)](#setColumnCount-int-) | Returns or sets number of columns in the text area. |
| [getColumnSpacing()](#getColumnSpacing--) | Returns or sets the space between text columns in the text area (in points). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Returns or sets the space between text columns in the text area (in points). |
| [getThreeDFormat()](#getThreeDFormat--) | Returns the ThreeDFormat object that represents 3d effect properties for a text. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Returns or set keeping text out of 3D scene entirely. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Returns or set keeping text out of 3D scene entirely. |
| [getRotationAngle()](#getRotationAngle--) | Specifies the custom rotation that is being applied to the text within the bounding box. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specifies the custom rotation that is being applied to the text within the bounding box. |
| [getTransform()](#getTransform--) | Gets or sets text wrapping shape. |
| [setTransform(byte value)](#setTransform-byte-) | Gets or sets text wrapping shape. |
| [getEffective()](#getEffective--) | Gets effective text frame formatting data with the inheritance applied. |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyle getTextStyle()
```


Visszaadja a szöveg stílusát. **Csak olvasható** [ITextStyle](../../com.aspose.slides/itextstyle).

**Visszatér:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```


Visszaadja vagy beállítja a bal margót (pontokban) egy TextFrame-ben. **Olvasás/írás** double.

**Visszatér:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```


Visszaadja vagy beállítja a bal margót (pontokban) egy TextFrame-ben. **Olvasás/írás** double.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```


Visszaadja vagy beállítja a jobb margót (pontokban) egy TextFrame-ben. **Olvasás/írás** double.

**Visszatér:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```


Visszaadja vagy beállítja a jobb margót (pontokban) egy TextFrame-ben. **Olvasás/írás** double.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```


Visszaadja vagy beállítja a felső margót (pontokban) egy TextFrame-ben. **Olvasás/írás** double.

**Visszatér:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```


Visszaadja vagy beállítja a felső margót (pontokban) egy TextFrame-ben. **Olvasás/írás** double.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```


Visszaadja vagy beállítja az alsó margót (pontokban) egy TextFrame-ben. **Olvasás/írás** double.

**Visszatér:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```


Visszaadja vagy beállítja az alsó margót (pontokban) egy TextFrame-ben. **Olvasás/írás** double.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```


Igaz, ha a szöveg be van törve a TextFrame margóin. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```


Igaz, ha a szöveg be van törve a TextFrame margóin. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```


Visszaadja vagy beállítja a függőleges horgony szöveget egy TextFrame-ben. **Olvasás/írás** [TextAnchorType](../../com.aspose.slides/textanchortype).

**Visszatér:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```


Visszaadja vagy beállítja a függőleges horgony szöveget egy TextFrame-ben. **Olvasás/írás** [TextAnchorType](../../com.aspose.slides/textanchortype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```


Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a dobozban. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Visszatér:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```


Ha NullableBool.True, akkor a szöveget vízszintesen középre kell helyezni a dobozban. **Olvasás/írás** [NullableBool](../../com.aspose.slides/nullablebool).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```


Meghatározza a szöveg tájolását. A vizuális szöveg forgatás eredő értéke ebből a tulajdonságból és a RotationAngle egyéni szögből kerül összegzésre. **Olvasás/írás** [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Visszatér:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```


Meghatározza a szöveg tájolását. A vizuális szöveg forgatás eredő értéke ebből a tulajdonságból és a RotationAngle egyéni szögből kerül összegzésre. **Olvasás/írás** [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```


Visszaadja vagy beállítja a szöveg autofit módját. **Olvasás/írás** [TextAutofitType](../../com.aspose.slides/textautofittype).

**Visszatér:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```


Visszaadja vagy beállítja a szöveg autofit módját. **Olvasás/írás** [TextAutofitType](../../com.aspose.slides/textautofittype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```


Visszaadja vagy beállítja az oszlopszámot a szövegterületen. Ennek az értéknek pozitív számnak kell lennie. Különben az érték nullára lesz állítva. A 0 érték nem definiált értéket jelent. **Olvasás/írás** int.

**Visszatér:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```


Visszaadja vagy beállítja az oszlopszámot a szövegterületen. Ennek az értéknek pozitív számnak kell lennie. Különben az érték nullára lesz állítva. A 0 érték nem definiált értéket jelent. **Olvasás/írás** int.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```


Visszaadja vagy beállítja a szövegoszlopok közötti távolságot a szövegterületen (pontokban). Ez csak akkor érvényes, ha több mint 1 oszlop van. Ennek az értéknek pozitív számnak kell lennie. Különben az érték nullára lesz állítva. **Olvasás/írás** double.

**Visszatér:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```


Visszaadja vagy beállítja a szövegoszlopok közötti távolságot a szövegterületen (pontokban). Ez csak akkor érvényes, ha több mint 1 oszlop van. Ennek az értéknek pozitív számnak kell lennie. Különben az érték nullára lesz állítva. **Olvasás/írás** double.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```


Visszaadja a ThreeDFormat objektumot, amely a szöveg 3D-effektus tulajdonságait képviseli. **Csak olvasható** [IThreeDFormat](../../com.aspose.slides/ithreedformat).

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      IAutoShape autoShape = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 10, 20, 400, 300);
>      ITextFrame textFrame = autoShape.getTextFrame();
>      textFrame.setText("Aspose.Slide Test Text");
>      // Állítsa be a szöveg átalakítását
>      textFrame.getTextFrameFormat().setTransform(TextShapeType.ArchUpPour);
>      // Állítsa be az extrúziót
>      textFrame.getTextFrameFormat().getThreeDFormat().getExtrusionColor().setColor(Color.ORANGE);
>      textFrame.getTextFrameFormat().getThreeDFormat().setExtrusionHeight(6);
>      // Állítsa be a kontúrt
>      textFrame.getTextFrameFormat().getThreeDFormat().getContourColor().setColor(Color.DARK_GRAY);
>      textFrame.getTextFrameFormat().getThreeDFormat().setContourWidth(1.5);
>      // Állítsa be a mélységet
>      textFrame.getTextFrameFormat().getThreeDFormat().setDepth(3);
>      // Állítsa be az anyagot
>      textFrame.getTextFrameFormat().getThreeDFormat().setMaterial(MaterialPresetType.Plastic);
>      // Állítsa be a világítást
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setDirection(LightingDirection.Top);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setLightType(LightRigPresetType.Balanced);
>      textFrame.getTextFrameFormat().getThreeDFormat().getLightRig().setRotation(0, 0, 40);
>      // Állítsa be a kamera típusát
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


Visszaadja vagy beállítja, hogy a szöveget teljesen a 3D-jelenetből kizárja. **Olvasás/írás** boolean.

**Visszatér:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```


Visszaadja vagy beállítja, hogy a szöveget teljesen a 3D-jelenetből kizárja. **Olvasás/írás** boolean.

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```


Meghatározza a szöveghez a határoló keretben alkalmazott egyéni forgást. Ha nincs megadva, akkor a kísérő alakzat forgása lesz használva. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Azaz az alakzat kaphat forgást, míg a szöveg is saját forgással rendelkezik. A vizuális szöveg forgatás eredő értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából kerül összegzésre. **Olvasás/írás** float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Visszatér:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```


Meghatározza a szöveghez a határoló keretben alkalmazott egyéni forgást. Ha nincs megadva, akkor a kísérő alakzat forgása lesz használva. Ha meg van adva, akkor ez függetlenül az alakzattól kerül alkalmazásra. Azaz az alakzat kaphat forgást, míg a szöveg is saját forgással rendelkezik. A vizuális szöveg forgatás eredő értéke ebből a tulajdonságból és a TextVerticalType előre definiált függőleges típusából kerül összegzésre. **Olvasás/írás** float.

--------------------

> ```
> Tekintse meg azt az esetet, amikor egy alakzatra 90 fokos óramutató járásával megegyező forgatás van alkalmazva. 
>  Ezen felül a szövegtörzs maga -90 fokos 
>  ellentétes irányú (counter-clockwise) forgatást kap. Ekkor a keletkezett alakzat úgy tűnik,
>  mintha el lenne forgatva, de a benne lévő szöveg úgy jelenik meg, mintha egyáltalán nem lett volna elforgatva.
```

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```


Visszaadja vagy beállítja a szöveg körbefuttatásának alakját. **Olvasás/írás** [TextShapeType](../../com.aspose.slides/textshapetype).

**Visszatér:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```


Visszaadja vagy beállítja a szöveg körbefuttatásának alakját. **Olvasás/írás** [TextShapeType](../../com.aspose.slides/textshapetype).

**Paraméterek:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```


Visszaadja a hatékony text frame formázási adatokat az öröklődés alkalmazásával.

**Visszatér:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).