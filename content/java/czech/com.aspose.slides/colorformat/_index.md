---
title: ColorFormat
second_title: Aspose.Slides pro Java API Reference
description: Reprezentuje barvu používanou v prezentaci.
type: docs
url: /cs/com.aspose.slides/colorformat/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechny implementované rozhraní:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

Reprezentuje barvu používanou v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColorType()](#getColorType--) | Vrací nebo nastavuje metodu definice barvy. |
| [setColorType(int value)](#setColorType-int-) | Vrací nebo nastavuje metodu definice barvy. |
| [getColor()](#getColor--) | Vrací výslednou barvu (s aplikovanými všemi transformacemi barvy). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Vrací výslednou barvu (s aplikovanými všemi transformacemi barvy). |
| [getPresetColor()](#getPresetColor--) | Vrací nebo nastavuje předvolbu barvy. |
| [setPresetColor(int value)](#setPresetColor-int-) | Vrací nebo nastavuje předvolbu barvy. |
| [getSystemColor()](#getSystemColor--) | Vrací nebo nastavuje barvu určenou systémovou tabulkou barev. |
| [setSystemColor(int value)](#setSystemColor-int-) | Vrací nebo nastavuje barvu určenou systémovou tabulkou barev. |
| [getSchemeColor()](#getSchemeColor--) | Vrací nebo nastavuje barvu určenou schématem barev. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Vrací nebo nastavuje barvu určenou schématem barev. |
| [getR()](#getR--) | Vrací nebo nastavuje červenou složku barvy. |
| [setR(byte value)](#setR-byte-) | Vrací nebo nastavuje červenou složku barvy. |
| [getG()](#getG--) | Vrací nebo nastavuje zelenou složku barvy. |
| [setG(byte value)](#setG-byte-) | Vrací nebo nastavuje zelenou složku barvy. |
| [getB()](#getB--) | Vrací nebo nastavuje modrou složku barvy. |
| [setB(byte value)](#setB-byte-) | Vrací nebo nastavuje modrou složku barvy. |
| [getFloatR()](#getFloatR--) | Vrací nebo nastavuje červenou složku barvy. |
| [setFloatR(float value)](#setFloatR-float-) | Vrací nebo nastavuje červenou složku barvy. |
| [getFloatG()](#getFloatG--) | Vrací nebo nastavuje zelenou složku barvy. |
| [setFloatG(float value)](#setFloatG-float-) | Vrací nebo nastavuje zelenou složku barvy. |
| [getFloatB()](#getFloatB--) | Vrací nebo nastavuje modrou složku barvy. |
| [setFloatB(float value)](#setFloatB-float-) | Vrací nebo nastavuje modrou složku barvy. |
| [getHue()](#getHue--) | Vrací nebo nastavuje odstín barvy v HSL reprezentaci. |
| [setHue(float value)](#setHue-float-) | Vrací nebo nastavuje odstín barvy v HSL reprezentaci. |
| [getSaturation()](#getSaturation--) | Vrací nebo nastavuje sytost barvy v HSL reprezentaci. |
| [setSaturation(float value)](#setSaturation-float-) | Vrací nebo nastavuje sytost barvy v HSL reprezentaci. |
| [getLuminance()](#getLuminance--) | Vrací nebo nastavuje jas barvy v HSL reprezentaci. |
| [setLuminance(float value)](#setLuminance-float-) | Vrací nebo nastavuje jas barvy v HSL reprezentaci. |
| [getColorTransform()](#getColorTransform--) | Vrací kolekci transformací barvy aplikovaných na barvu. |
| [toString(int format)](#toString-int-) | Vrací řetězec, který představuje aktuální formát barvy. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Zkopíruje formát barvy z "color". |
| [equals(Object obj)](#equals-java.lang.Object-) | Kontroluje rovnost se zadaným objektem. |
| [hashCode()](#hashCode--) | Vrací hash kód. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |
### getColorType() {#getColorType--}
```
public final int getColorType()
```

Vrací nebo nastavuje metodu definice barvy. Čtení/zápis [ColorType](../../com.aspose.slides/colortype).

**Vrací:**
int
### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

Vrací nebo nastavuje metodu definice barvy. Čtení/zápis [ColorType](../../com.aspose.slides/colortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

Vrací výslednou barvu (s aplikovanými všemi transformacemi barvy). Nastaví RGB barvy a vymaže všechny transformace barev. Čtení/zápis java.awt.Color.

**Vrací:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Vrací výslednou barvu (s aplikovanými všemi transformacemi barvy). Nastaví RGB barvy a vymaže všechny transformace barev. Čtení/zápis java.awt.Color.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

Vrací nebo nastavuje předvolbu barvy. Čtení/zápis [PresetColor](../../com.aspose.slides/presetcolor).

**Vrací:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

Vrací nebo nastavuje předvolbu barvy. Čtení/zápis [PresetColor](../../com.aspose.slides/presetcolor).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

Vrací nebo nastavuje barvu určenou systémovou tabulkou barev. Čtení/zápis [SystemColor](../../com.aspose.slides/systemcolor).

**Vrací:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

Vrací nebo nastavuje barvu určenou systémovou tabulkou barev. Čtení/zápis [SystemColor](../../com.aspose.slides/systemcolor).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

Vrací nebo nastavuje barvu určenou schématem barev. Čtení/zápis [SchemeColor](../../com.aspose.slides/schemecolor).

**Vrací:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

Vrací nebo nastavuje barvu určenou schématem barev. Čtení/zápis [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

Vrací nebo nastavuje červenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  byte .

**Vrací:**
byte
### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

Vrací nebo nastavuje červenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  byte .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

Vrací nebo nastavuje zelenou složku barvy. Všechny transformace barev jsou ignorovány.

**Vrací:**
byte
### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

Vrací nebo nastavuje zelenou složku barvy. Všechny transformace barev jsou ignorovány.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

Vrací nebo nastavuje modrou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  byte .

**Vrací:**
byte
### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

Vrací nebo nastavuje modrou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  byte .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

Vrací nebo nastavuje červenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Vrací:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

Vrací nebo nastavuje červenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

Vrací nebo nastavuje zelenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Vrací:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

Vrací nebo nastavuje zelenou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

Vrací nebo nastavuje modrou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Vrací:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

Vrací nebo nastavuje modrou složku barvy. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

Vrací nebo nastavuje odstín barvy v HSL reprezentaci. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Vrací:**
float
### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

Vrací nebo nastavuje odstín barvy v HSL reprezentaci. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

Vrací nebo nastavuje sytost barvy v HSL reprezentaci. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Vrací:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

Vrací nebo nastavuje sytost barvy v HSL reprezentaci. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

Vrací nebo nastavuje jas barvy v HSL reprezentaci. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Vrací:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

Vrací nebo nastavuje jas barvy v HSL reprezentaci. Všechny transformace barev jsou ignorovány. Čtení/zápis  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

Vrací kolekci transformací barvy aplikovaných na barvu. Pouze ke čtení [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Vrací:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

Vrací řetězec, který představuje aktuální formát barvy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| format | int | Typ formátu řetězce barvy. |

**Vrací:**
java.lang.String - řetězec, který představuje aktuální formát barvy.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

Zkopíruje formát barvy z "color".

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Kontroluje rovnost se zadaným objektem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| obj | java.lang.Object | Objekt. |

**Vrací:**
boolean - True if objects are equal, otherwise false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Vrací hash kód.

**Vrací:**
int - Hash code.
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze ke čtení long.

**Vrací:**
long
### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```




**Vrací:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)
### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Vrací nadřazený IPresentationComponent. Pouze ke čtení [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Vrací:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)