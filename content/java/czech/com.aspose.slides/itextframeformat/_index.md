---
title: ITextFrameFormat
second_title: Aspose.Slides pro Java – API Reference
description: Obsahuje vlastnosti formátování TextFrames.
type: docs
url: /cs/com.aspose.slides/itextframeformat/
---```
public interface ITextFrameFormat
```

Obsahuje vlastnosti formátování TextFrame.

## Metody

| Metoda | Popis |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Vrací styl textu. |
| [getMarginLeft()](#getMarginLeft--) | Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. |
| [getMarginRight()](#getMarginRight--) | Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. |
| [getMarginTop()](#getMarginTop--) | Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Vrací nebo nastavuje dolní okraj (v bodech) v TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Vrací nebo nastavuje dolní okraj (v bodech) v TextFrame. |
| [getWrapText()](#getWrapText--) | Pravda, pokud je text zalomen na okrajích TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Pravda, pokud je text zalomen na okrajích TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. |
| [getCenterText()](#getCenterText--) | Pokud NullableBool.True, text by měl být horizontálně vycentrován v rámečku. |
| [setCenterText(byte value)](#setCenterText-byte-) | Pokud NullableBool.True, text by měl být horizontálně vycentrován v rámečku. |
| [getTextVerticalType()](#getTextVerticalType--) | Určuje orientaci textu. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Určuje orientaci textu. |
| [getAutofitType()](#getAutofitType--) | Vrací nebo nastavuje režim automatického přizpůsobení textu. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Vrací nebo nastavuje režim automatického přizpůsobení textu. |
| [getColumnCount()](#getColumnCount--) | Vrací nebo nastavuje počet sloupců v textové oblasti. |
| [setColumnCount(int value)](#setColumnCount-int-) | Vrací nebo nastavuje počet sloupců v textové oblasti. |
| [getColumnSpacing()](#getColumnSpacing--) | Vrací nebo nastavuje mezery mezi sloupci textu v textové oblasti (v bodech). |
| [setColumnSpacing(double value)](#setColumnSpacing-double-) | Vrací nebo nastavuje mezery mezi sloupci textu v textové oblasti (v bodech). |
| [getThreeDFormat()](#getThreeDFormat--) | Vrací objekt ThreeDFormat, který představuje vlastnosti 3D efektu pro text. |
| [getKeepTextFlat()](#getKeepTextFlat--) | Vrací nebo nastavuje úplné vyloučení textu ze 3D scény. |
| [setKeepTextFlat(boolean value)](#setKeepTextFlat-boolean-) | Vrací nebo nastavuje úplné vyloučení textu ze 3D scény. |
| [getRotationAngle()](#getRotationAngle--) | Určuje vlastní rotaci aplikovanou na text uvnitř ohraničujícího rámečku. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Určuje vlastní rotaci aplikovanou na text uvnitř ohraničujícího rámečku. |
| [getTransform()](#getTransform--) | Vrací nebo nastavuje tvar zalamování textu. |
| [setTransform(byte value)](#setTransform-byte-) | Vrací nebo nastavuje tvar zalamování textu. |
| [getEffective()](#getEffective--) | Vrací efektivní data formátování textového rámce s aplikovaným děděním. |

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

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Čtení a zápis double.

**Vrací:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Čtení a zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Čtení a zápis double.

**Vrací:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Čtení a zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Čtení a zápis double.

**Vrací:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Čtení a zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Vrací nebo nastavuje dolní okraj (v bodech) v TextFrame. Čtení a zápis double.

**Vrací:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Vrací nebo nastavuje dolní okraj (v bodech) v TextFrame. Čtení a zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Pravda, pokud je text zalomen na okrajích TextFrame. Čtení a zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Pravda, pokud je text zalomen na okrajích TextFrame. Čtení a zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Čtení a zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Čtení a zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Pokud NullableBool.True, text by měl být horizontálně vycentrován v rámečku. Čtení a zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Pokud NullableBool.True, text by měl být horizontálně vycentrován v rámečku. Čtení a zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je součtem této vlastnosti a vlastnosti RotationAngle. Čtení a zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Vrací:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je součtem této vlastnosti a vlastnosti RotationAngle. Čtení a zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Čtení a zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Vrací:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Čtení a zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Vrací nebo nastavuje počet sloupců v textové oblasti. Hodnota musí být kladná; jinak se nastaví na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Čtení a zápis int.

**Vrací:**
int

### setColumnCount(int value) {#setColumnCount-int-}
```
public abstract void setColumnCount(int value)
```

Vrací nebo nastavuje počet sloupců v textové oblasti. Hodnota musí být kladná; jinak se nastaví na nulu. Hodnota 0 znamená nedefinovanou hodnotu. Čtení a zápis int.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getColumnSpacing() {#getColumnSpacing--}
```
public abstract double getColumnSpacing()
```

Vrací nebo nastavuje mezery mezi sloupci textu v textové oblasti (v bodech). Používá se jen když je více než 1 sloupec. Hodnota musí být kladná; jinak se nastaví na nulu. Čtení a zápis double.

**Vrací:**
double

### setColumnSpacing(double value) {#setColumnSpacing-double-}
```
public abstract void setColumnSpacing(double value)
```

Vrací nebo nastavuje mezery mezi sloupci textu v textové oblasti (v bodech). Používá se jen když je více než 1 sloupec. Hodnota musí být kladná; jinak se nastaví na nulu. Čtení a zápis double.

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

Vrací nebo nastavuje úplné vyloučení textu ze 3D scény. Čtení a zápis boolean.

**Vrací:**
boolean

### setKeepTextFlat(boolean value) {#setKeepTextFlat-boolean-}
```
public abstract void setKeepTextFlat(boolean value)
```

Vrací nebo nastavuje úplné vyloučení textu ze 3D scény. Čtení a zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Určuje vlastní rotaci aplikovanou na text uvnitř ohraničujícího rámečku. Pokud není zadána, použije se rotace přidruženého tvaru. Pokud je zadána, aplikuje se nezávisle na tvaru. Výsledná hodnota vizuální rotace textu je součtem této vlastnosti a předdefinovaného vertikálního typu v TextVerticalType. Čtení a zápis float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Vrací:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Určuje vlastní rotaci aplikovanou na text uvnitř ohraničujícího rámečku. Pokud není zadána, použije se rotace přidruženého tvaru. Pokud je zadána, aplikuje se nezávisle na tvaru. Výsledná hodnota vizuální rotace textu je součtem této vlastnosti a předdefinovaného vertikálního typu v TextVerticalType. Čtení a zápis float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getTransform() {#getTransform--}
```
public abstract byte getTransform()
```

Vrací nebo nastavuje tvar zalamování textu. Čtení a zápis [TextShapeType](../../com.aspose.slides/textshapetype).

**Vrací:**
byte

### setTransform(byte value) {#setTransform-byte-}
```
public abstract void setTransform(byte value)
```

Vrací nebo nastavuje tvar zalamování textu. Čtení a zápis [TextShapeType](../../com.aspose.slides/textshapetype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getEffective() {#getEffective--}
```
public abstract ITextFrameFormatEffectiveData getEffective()
```

Vrací efektivní data formátování textového rámce s aplikovaným děděním.

**Vrací:**
[ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata) - A [ITextFrameFormatEffectiveData](../../com.aspose.slides/itextframeformateffectivedata).