---
title: ITextFrameFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Obsahuje formátovací vlastnosti TextFrames.
type: docs
url: /cs/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Obsahuje formátovací vlastnosti TextFrame.

## Metody

| Metoda | Popis |
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

Vrací styl textu. Pouze pro čtení [ITextStyle](../../com.aspose.slides/itextstyle).

**Vrací:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Vrací:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Vrací:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Vrací:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Vrací:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True pokud je text zalomen na okrajích TextFrame. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True pokud je text zalomen na okrajích TextFrame. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Čtení/Zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Čtení/Zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Pokud NullableBool.True, pak by měl být text vodorovně vycentrován v rámečku. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Pokud NullableBool.True, pak by měl být text vodorovně vycentrován v rámečku. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Určuje orientaci textu. Výsledná hodnota vizuálního otočení textu je shrnuta z této vlastnosti a vlastního úhlu ve vlastnosti RotationAngle. Čtení/Zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Vrací:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Určuje orientaci textu. Výsledná hodnota vizuálního otočení textu je shrnuta z této vlastnosti a vlastního úhlu ve vlastnosti RotationAngle. Čtení/Zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Čtení/Zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Vrací:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Čtení/Zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Vrací nebo nastavuje počet sloupců v textové oblasti. Tato hodnota musí být kladné číslo. V opačném případě bude hodnota nastavena na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/Zápis int.

**Vrací:**
int
### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Vrací nebo nastavuje počet sloupců v textové oblasti. Tato hodnota musí být kladné číslo. V opačném případě bude hodnota nastavena na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Čtení/Zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Vrací nebo nastavuje prostor mezi sloupci textu v textové oblasti (v bodech). Toto by se mělo použít jen, pokud je přítomno více než 1 sloupec. Tato hodnota musí být kladné číslo. V opačném případě bude hodnota nastavena na nulu. Čtení/Zápis double.

**Vrací:**
double
### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Vrací nebo nastavuje prostor mezi sloupci textu v textové oblasti (v bodech). Toto by se mělo použít jen, pokud je přítomno více než 1 sloupec. Tato hodnota musí být kladné číslo. V opačném případě bude hodnota nastavena na nulu. Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |
### getThreeDFormat() {#getThreeDFormat--}
```
public abstract IThreeDFormat getThreeDFormat()
```

Vrací objekt ThreeDFormat, který představuje vlastnosti 3D efektu pro text. Pouze pro čtení [IThreeDFormat](../../com.aspose.slides/ithreedformat).

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
### getKeepTextFlat() {#getKeepTextFlat--}
```
public abstract boolean getKeepTextFlat()
```

Vrací nebo nastavuje zachování textu mimo 3D scénu úplně. Čtení/Zápis boolean.

**Vrací:**
boolean
### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Vrací nebo nastavuje zachování textu mimo 3D scénu úplně. Čtení/Zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Určuje vlastní rotaci, která se aplikuje na text v ohraničujícím rámečku. Pokud není specifikována, použije se rotace odpovídajícího tvaru. Pokud je specifikována, pak se aplikuje nezávisle na tvaru. To znamená, že tvar může mít aplikovanou rotaci navíc k rotaci samotného textu. Výsledná hodnota vizuálního otočení textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Čtení/Zápis float.

--------------------

> ```
> Zvažte případ, kdy má tvar aplikovanou rotaci 90 stupňů po směru hodinových ručiček. 
>  K tomu má tělo textu samotné aplikovanou rotaci -90 stupňů 
>  proti směru hodinových ručiček aplikovanou na něj. Pak by výsledný tvar vypadal, že je
>  otočen, ale text uvnitř by se zdál, že vůbec nebyl otočen.
> ```


**Vrací:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Určuje vlastní rotaci, která se aplikuje na text v ohraničujícím rámečku. Pokud není specifikována, použije se rotace odpovídajícího tvaru. Pokud je specifikována, pak se aplikuje nezávisle na tvaru. To znamená, že tvar může mít aplikovanou rotaci navíc k rotaci samotného textu. Výsledná hodnota vizuálního otočení textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu ve vlastnosti TextVerticalType. Čtení/Zápis float.

--------------------

> ```
> Zvažte případ, kdy má tvar aplikovanou rotaci 90 stupňů po směru hodinových ručiček. 
>  K tomu má tělo textu samotné rotaci -90 stupňů 
>  proti směru hodinových ručiček aplikovanou na něj. Pak by výsledný tvar vypadal, 
>  že je otočen, ale text uvnitř by se zdál, že vůbec nebyl otočen.
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Vrací nebo nastavuje tvar zalamování textu. Čtení/Zápis [TextShapeType](../../com.aspose.slides/textshapetype).

**Vrací:**
byte
### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Vrací nebo nastavuje tvar zalamování textu. Čtení/Zápis [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |
### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Vrací efektivní data formátování textového rámce s aplikovanou dědičností.

**Vrací:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).