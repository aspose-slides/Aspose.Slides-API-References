---
title: ColorFormat
second_title: Aspose.Slides Androidra Java API referencia
description: Egy prezentációban használt színt képvisel.
type: docs
url: /hu/com.aspose.slides/colorformat/
---
**Öröklés:**  
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Minden megvalósított interfész:**  
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

A prezentációban használt színt reprezentál.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getColorType()](#getColorType--) | Visszaadja vagy beállítja a színdefiníció módját. |
| [setColorType(int value)](#setColorType-int-) | Visszaadja vagy beállítja a színdefiníció módját. |
| [getColor()](#getColor--) | Visszaadja az eredmény színt (az összes színtranszformáció alkalmazásával). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Visszaadja az eredmény színt (az összes színtranszformáció alkalmazásával). |
| [getPresetColor()](#getPresetColor--) | Visszaadja vagy beállítja a szín előre beállított értékét. |
| [setPresetColor(int value)](#setPresetColor-int-) | Visszaadja vagy beállítja a szín előre beállított értékét. |
| [getSystemColor()](#getSystemColor--) | Visszaadja vagy beállítja a rendszer színtáblában azonosított színt. |
| [setSystemColor(int value)](#setSystemColor-int-) | Visszaadja vagy beállítja a rendszer színtáblában azonosított színt. |
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
| [getHue()](#getHue--) | Visszaadja vagy beállítja egy szín árnyalat komponensét HSL reprezentációban. |
| [setHue(float value)](#setHue-float-) | Visszaadja vagy beállítja egy szín árnyalat komponensét HSL reprezentációban. |
| [getSaturation()](#getSaturation--) | Visszaadja vagy beállítja egy szín telítettség komponensét HSL reprezentációban. |
| [setSaturation(float value)](#setSaturation-float-) | Visszaadja vagy beállítja egy szín telítettség komponensét HSL reprezentációban. |
| [getLuminance()](#getLuminance--) | Visszaadja vagy beállítja egy szín fényerő komponensét HSL reprezentációban. |
| [setLuminance(float value)](#setLuminance-float-) | Visszaadja vagy beállítja egy szín fényerő komponensét HSL reprezentációban. |
| [getColorTransform()](#getColorTransform--) | Visszaadja a színre alkalmazott színtranszformációk gyűjteményét. |
| [toString(int format)](#toString-int-) | Visszaad egy String-et, amely a jelenlegi színformátumot reprezentálja. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Másolja a színformátumot a "color"-ból. |
| [equals(Object obj)](#equals-java.lang.Object-) | Ellenőrzi az egyenlőséget a megadott objektummal. |
| [hashCode()](#hashCode--) | Visszaadja a hash kódot. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getColorType() {#getColorType--}
```
public final int getColorType()
```

Visszaadja vagy beállítja a színdefiníció módját. Olvasás/írás [ColorType](../../com.aspose.slides/colortype).

**Visszatér:**  
int
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

Visszaadja vagy beállítja a színdefiníció módját. Olvasás/írás [ColorType](../../com.aspose.slides/colortype).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Integer getColor()
```

Visszaadja az eredmény színt (az összes színtranszformáció alkalmazásával). Beállítja az RGB színeket és törli az összes színtranszformációt. Olvasás/írás java.lang.Integer.

**Visszatér:**  
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public final void setColor(Integer value)
```

Visszaadja az eredmény színt (az összes színtranszformáció alkalmazásával). Beállítja az RGB színeket és törli az összes színtranszformációt. Olvasás/írás java.lang.Integer.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

Visszaadja vagy beállítja a szín előre beállított értékét. Olvasás/írás [PresetColor](../../com.aspose.slides/presetcolor).

**Visszatér:**  
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

Visszaadja vagy beállítja a szín előre beállított értékét. Olvasás/írás [PresetColor](../../com.aspose.slides/presetcolor).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

Visszaadja vagy beállítja a rendszer színtáblában azonosított színt. Olvasás/írás [SystemColor](../../com.aspose.slides/systemcolor).

**Visszatér:**  
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

Visszaadja vagy beállítja a rendszer színtáblában azonosított színt. Olvasás/írás [SystemColor](../../com.aspose.slides/systemcolor).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

Visszaadja vagy beállítja egy színséma által azonosított színt. Olvasás/írás [SchemeColor](../../com.aspose.slides/schemecolor).

**Visszatér:**  
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

Visszaadja vagy beállítja egy színséma által azonosított színt. Olvasás/írás [SchemeColor](../../com.aspose.slides/schemecolor).

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

Visszaadja vagy beállítja egy szín vörös komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  byte .

**Visszatér:**  
byte
### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

Visszaadja vagy beállítja egy szín vörös komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  byte .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

Visszaadja vagy beállítja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül van hagyva.

**Visszatér:**  
byte
### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

Visszaadja vagy beállítja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül van hagyva.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

Visszaadja vagy beállítja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  byte .

**Visszatér:**  
byte
### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

Visszaadja vagy beállítja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  byte .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

Visszaadja vagy beállítja egy szín vörös komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Visszatér:**  
float
### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

Visszaadja vagy beállítja egy szín vörös komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

Visszaadja vagy beállítja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Visszatér:**  
float
### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

Visszaadja vagy beállítja egy szín zöld komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

Visszaadja vagy beállítja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Visszatér:**  
float
### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

Visszaadja vagy beállítja egy szín kék komponensét. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

Visszaadja vagy beállítja egy szín árnyalat komponensét HSL reprezentációban. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Visszatér:**  
float
### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

Visszaadja vagy beállítja egy szín árnyalat komponensét HSL reprezentációban. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

Visszaadja vagy beállítja egy szín telítettség komponensét HSL reprezentációban. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Visszatér:**  
float
### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

Visszaadja vagy beállítja egy szín telítettség komponensét HSL reprezentációban. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

Visszaadja vagy beállítja egy szín fényerő komponensét HSL reprezentációban. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Visszatér:**  
float
### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

Visszaadja vagy beállítja egy szín fényerő komponensét HSL reprezentációban. Minden színtranszformáció figyelmen kívül van hagyva. Olvasás/írás  float .

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

Visszaadja a színre alkalmazott színtranszformációk gyűjteményét. Csak-olvasás [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Visszatér:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

Visszaad egy String-et, amely a jelenlegi színformátumot reprezentálja.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| format | int | A szín string formátum típusa. |

**Visszatér:**  
java.lang.String - Egy string, amely a jelenlegi színformátumot reprezentálja.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

Másolja a színformátumot a "color"-ból.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Ellenőrzi az egyenlőséget a megadott objektummal.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | java.lang.Object | Objektum. |

**Visszatér:**  
boolean - Igaz, ha az objektumok egyenlőek, egyébként hamis.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Visszaadja a hash kódot.

**Visszatér:**  
int - Hash kód.
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verzió. Csak-olvasás long.

**Visszatér:**  
long
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**Visszatér:**  
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Visszaadja a szülő IPresentationComponent-et. Csak-olvasás [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Visszatér:**  
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)