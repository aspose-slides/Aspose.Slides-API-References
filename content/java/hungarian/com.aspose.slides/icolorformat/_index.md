---
title: IColorFormat
second_title: Aspose.Slides Java API hivatkozás
description: A prezentációban használt színt képviseli.
type: docs
url: /hu/com.aspose.slides/icolorformat/
---
**Minden megvalósított interfész:**  
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

A prezentációban használt színt képviseli.

## Metódusok

| Módszer | Leírás |
| --- | --- |
| [getColorType()](#getColorType--) | Visszaadja vagy beállítja a színdefiníció módját. |
| [setColorType(int value)](#setColorType-int-) | Visszaadja vagy beállítja a színdefiníció módját. |
| [getColor()](#getColor--) | Visszaadja az eredmény színt (az összes színtranszformáció alkalmazásával). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Visszaadja az eredmény színt (az összes színtranszformáció alkalmazásával). |
| [getPresetColor()](#getPresetColor--) | Visszaadja vagy beállítja a szín előbeállítását. |
| [setPresetColor(int value)](#setPresetColor-int-) | Visszaadja vagy beállítja a szín előbeállítását. |
| [getSystemColor()](#getSystemColor--) | Visszaadja vagy beállítja a rendszer szín táblázata által azonosított színt. |
| [setSystemColor(int value)](#setSystemColor-int-) | Visszaadja vagy beállítja a rendszer szín táblázata által azonosított színt. |
| [getSchemeColor()](#getSchemeColor--) | Visszaadja vagy beállítja egy színséma által azonosított színt. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Visszaadja vagy beállítja egy színséma által azonosított színt. |
| [getR()](#getR--) | Visszaadja vagy beállítja egy szín vörös komponensét. |
| [setR(byte value)](#setR-byte-) | Visszaadja vagy beállítja egy szín vörös komponensét. |
| [getG()](#getG--) | Visszaadja vagy beállítja egy szín zöld komponensét. |
| [setG(byte value)](#setG-byte-) | Visszaadja vagy beállítja egy szín zöld komponensét. |
| [getB()](#getB--) | Visszaadja vagy beállítja egy szín kék komponensét. |
| [setB(byte value)](#setB-byte-) | Visszaadja vagy beállítja egy szín kék komponensét. |
| [getFloatR()](#getFloatR--) | Visszaadja vagy beállítja egy szín vörös komponensét. |
| [setFloatR(float value)](#setFloatR-float-) | Visszaadja vagy beállítja egy szín vörös komponensét. |
| [getFloatG()](#getFloatG--) | Visszaadja vagy beállítja egy szín zöld komponensét. |
| [setFloatG(float value)](#setFloatG-float-) | Visszaadja vagy beállítja egy szín zöld komponensét. |
| [getFloatB()](#getFloatB--) | Visszaadja vagy beállítja egy szín kék komponensét. |
| [setFloatB(float value)](#setFloatB-float-) | Visszaadja vagy beállítja egy szín kék komponensét. |
| [getHue()](#getHue--) | Visszaadja vagy beállítja a szín árnyalat komponensét HSL ábrázolásban. |
| [setHue(float value)](#setHue-float-) | Visszaadja vagy beállítja a szín árnyalat komponensét HSL ábrázolásban. |
| [getSaturation()](#getSaturation--) | Visszaadja vagy beállítja a szín telítettség komponensét HSL ábrázolásban. |
| [setSaturation(float value)](#setSaturation-float-) | Visszaadja vagy beállítja a szín telítettség komponensét HSL ábrázolásban. |
| [getLuminance()](#getLuminance--) | Visszaadja vagy beállítja a szín fényesség komponensét HSL ábrázolásban. |
| [setLuminance(float value)](#setLuminance-float-) | Visszaadja vagy beállítja a szín fényesség komponensét HSL ábrázolásban. |
| [getColorTransform()](#getColorTransform--) | Visszaadja a színre alkalmazott színtranszformációk gyűjteményét. |
| [toString(int format)](#toString-int-) | Visszaad egy Stringet, amely az aktuális színformátumot reprezentálja. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Másolja a színformátumot a "color"-ból. |

### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Visszaadja vagy beállítja a színdefiníció módját. Olvasás/írás [ColorType](../../com.aspose.slides/colortype).

**Visszatér:**
int

### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Visszaadja vagy beállítja a színdefiníció módját. Olvasás/írás [ColorType](../../com.aspose.slides/colortype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Visszaadja az eredmény színt (az összes színtranszformáció alkalmazásával). Beállítja az RGB színeket és törli az összes színtranszformációt. Olvasás/írás java.awt.Color.

**Visszatér:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Visszaadja az eredmény színt (az összes színtranszformáció alkalmazásával). Beállítja az RGB színeket és törli az összes színtranszformációt. Olvasás/írás java.awt.Color.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Visszaadja vagy beállítja a szín előbeállítását. Olvasás/írás [PresetColor](../../com.aspose.slides/presetcolor).

**Visszatér:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Visszaadja vagy beállítja a szín előbeállítását. Olvasás/írás [PresetColor](../../com.aspose.slides/presetcolor).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Visszaadja vagy beállítja a rendszer szín táblázata által azonosított színt. Olvasás/írás [SystemColor](../../com.aspose.slides/systemcolor).

**Visszatér:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Visszaadja vagy beállítja a rendszer szín táblázata által azonosított színt. Olvasás/írás [SystemColor](../../com.aspose.slides/systemcolor).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Visszaadja vagy beállítja egy színséma által azonosított színt. Olvasás/írás [SchemeColor](../../com.aspose.slides/schemecolor).

**Visszatér:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Visszaadja vagy beállítja egy színséma által azonosított színt. Olvasás/írás [SchemeColor](../../com.aspose.slides/schemecolor).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Visszaadja vagy beállítja egy szín vörös komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás byte.

**Visszatér:**
byte

### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Visszaadja vagy beállítja egy szín vörös komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Visszaadja vagy beállítja egy szín zöld komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás byte.

**Visszatér:**
byte

### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Visszaadja vagy beállítja egy szín zöld komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Visszaadja vagy beállítja egy szín kék komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás byte.

**Visszatér:**
byte

### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Visszaadja vagy beállítja egy szín kék komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás byte.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Visszaadja vagy beállítja egy szín vörös komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Visszatér:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Visszaadja vagy beállítja egy szín vörös komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Visszaadja vagy beállítja egy szín zöld komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Visszatér:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Visszaadja vagy beállítja egy szín zöld komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Visszaadja vagy beállítja egy szín kék komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Visszatér:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Visszaadja vagy beállítja egy szín kék komponensét. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Visszaadja vagy beállítja a szín árnyalat komponensét HSL ábrázolásban. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Visszatér:**
float

### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Visszaadja vagy beállítja a szín árnyalat komponensét HSL ábrázolásban. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Visszaadja vagy beállítja a szín telítettség komponensét HSL ábrázolásban. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Visszatér:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Visszaadja vagy beállítja a szín telítettség komponensét HSL ábrázolásban. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Visszaadja vagy beállítja a szín fényesség komponensét HSL ábrázolásban. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Visszatér:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Visszaadja vagy beállítja a szín fényesség komponensét HSL ábrázolásban. Az összes színtranszformáció figyelmen kívül van hagyva. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Csak olvasás [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Visszatér:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Visszaad egy Stringet, amely az aktuális színformátumot reprezentálja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | int | A szín karakterlánc formátum típusa. |

**Visszatér:**
java.lang.String - Egy string, amely az aktuális színformátumot reprezentálja.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Másolja a színformátumot a "color"-ból.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Szín [IColorFormat](../../com.aspose.slides/icolorformat) |