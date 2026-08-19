---
title: IColorFormat
second_title: Aspose.Slides pro Java – referenční příručka API
description: Representuje barvu používanou v prezentaci.
type: docs
url: /cs/com.aspose.slides/icolorformat/
---
**Všechny implementované rozhraní:**  
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Represents a color used in a presentation.
## Metody

| Method | Description |
| --- | --- |
| [getColorType()](#getColorType--) | Vrací nebo nastavuje metodu definice barvy. |
| [setColorType(int value)](#setColorType-int-) | Vrací nebo nastavuje metodu definice barvy. |
| [getColor()](#getColor--) | Vrací výslednou barvu (se všemi aplikovanými transformacemi barvy). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Vrací výslednou barvu (se všemi aplikovanými transformacemi barvy). |
| [getPresetColor()](#getPresetColor--) | Vrací nebo nastavuje přednastavenou barvu. |
| [setPresetColor(int value)](#setPresetColor-int-) | Vrací nebo nastavuje přednastavenou barvu. |
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
| [getHue()](#getHue--) | Vrací nebo nastavuje odstín barvy v reprezentaci HSL. |
| [setHue(float value)](#setHue-float-) | Vrací nebo nastavuje odstín barvy v reprezentaci HSL. |
| [getSaturation()](#getSaturation--) | Vrací nebo nastavuje složku sytosti barvy v reprezentaci HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Vrací nebo nastavuje složku sytosti barvy v reprezentaci HSL. |
| [getLuminance()](#getLuminance--) | Vrací nebo nastavuje komponentu jasu barvy v reprezentaci HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Vrací nebo nastavuje komponentu jasu barvy v reprezentaci HSL. |
| [getColorTransform()](#getColorTransform--) | Vrací kolekci transformací barvy aplikovaných na barvu. |
| [toString(int format)](#toString-int-) | Vrací řetězec, který představuje aktuální formát barvy. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Zkopíruje formát barvy z "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```


Vrací nebo nastavuje metodu definice barvy. Čtení/zápis [ColorType](../../com.aspose.slides/colortype).

**Vrací:**  
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```


Vrací nebo nastavuje metodu definice barvy. Čtení/zápis [ColorType](../../com.aspose.slides/colortype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


Vrací výslednou barvu (se všemi aplikovanými transformacemi barvy). Nastavuje RGB barvy a vymazává všechny transformace barvy. Čtení/zápis java.awt.Color.

**Vrací:**  
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Vrací výslednou barvu (se všemi aplikovanými transformacemi barvy). Nastavuje RGB barvy a vymazává všechny transformace barvy. Čtení/zápis java.awt.Color.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```


Vrací nebo nastavuje přednastavenou barvu. Čtení/zápis [PresetColor](../../com.aspose.slides/presetcolor).

**Vrací:**  
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```


Vrací nebo nastavuje přednastavenou barvu. Čtení/zápis [PresetColor](../../com.aspose.slides/presetcolor).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```


Vrací nebo nastavuje barvu určenou systémovou tabulkou barev. Čtení/zápis [SystemColor](../../com.aspose.slides/systemcolor).

**Vrací:**  
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```


Vrací nebo nastavuje barvu určenou systémovou tabulkou barev. Čtení/zápis [SystemColor](../../com.aspose.slides/systemcolor).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```


Vrací nebo nastavuje barvu určenou schématem barev. Čtení/zápis [SchemeColor](../../com.aspose.slides/schemecolor).

**Vrací:**  
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```


Vrací nebo nastavuje barvu určenou schématem barev. Čtení/zápis [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```


Vrací nebo nastavuje červenou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis byte.

**Vrací:**  
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```


Vrací nebo nastavuje červenou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis byte.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```


Vrací nebo nastavuje zelenou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis byte.

**Vrací:**  
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```


Vrací nebo nastavuje zelenou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis byte.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```


Vrací nebo nastavuje modrou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis byte.

**Vrací:**  
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```


Vrací nebo nastavuje modrou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis byte.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```


Vrací nebo nastavuje červenou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Vrací:**  
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```


Vrací nebo nastavuje červenou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```


Vrací nebo nastavuje zelenou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Vrací:**  
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```


Vrací nebo nastavuje zelenou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```


Vrací nebo nastavuje modrou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Vrací:**  
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```


Vrací nebo nastavuje modrou složku barvy. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```


Vrací nebo nastavuje odstín barvy v reprezentaci HSL. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Vrací:**  
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```


Vrací nebo nastavuje odstín barvy v reprezentaci HSL. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```


Vrací nebo nastavuje složku sytosti barvy v reprezentaci HSL. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Vrací:**  
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```


Vrací nebo nastavuje složku sytosti barvy v reprezentaci HSL. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```


Vrací nebo nastavuje komponentu jasu barvy v reprezentaci HSL. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Vrací:**  
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```


Vrací nebo nastavuje komponentu jasu barvy v reprezentaci HSL. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```


Vrací kolekci transformací barvy aplikovaných na barvu. Pouze pro čtení [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Vrací:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```


Vrací řetězec, který představuje aktuální formát barvy.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| format | int | Typ formátu řetězce barvy. |

**Vrací:**  
java.lang.String - Řetězec, který představuje aktuální formát barvy.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```


Zkopíruje formát barvy z "color".

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Barva [IColorFormat](../../com.aspose.slides/icolorformat) |