---
title: IColorFormat
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Reprezentuje barvu používanou v prezentaci.
type: docs
url: /cs/com.aspose.slides/icolorformat/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Reprezentuje barvu používanou v prezentaci.
## Metody

| Metoda | Popis |
| --- | --- |
| [getColorType()](#getColorType--) | Vrací nebo nastavuje metodu definice barvy. |
| [setColorType(int value)](#setColorType-int-) | Vrací nebo nastavuje metodu definice barvy. |
| [getColor()](#getColor--) | Vrací výslednou barvu (s aplikovanými všemi transformacemi barvy). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Vrací výslednou barvu (s aplikovanými všemi transformacemi barvy). |
| [getPresetColor()](#getPresetColor--) | Vrací nebo nastavuje předvolbu barvy. |
| [setPresetColor(int value)](#setPresetColor-int-) | Vrací nebo nastavuje předvolbu barvy. |
| [getSystemColor()](#getSystemColor--) | Vrací nebo nastavuje barvu určenou systémovou tabulkou barev. |
| [setSystemColor(int value)](#setSystemColor-int-) | Vrací nebo nastavuje barvu určenou systémovou tabulkou barev. |
| [getSchemeColor()](#getSchemeColor--) | Vrací nebo nastavuje barvu určenou barevným schématem. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Vrací nebo nastavuje barvu určenou barevným schématem. |
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
| [getHue()](#getHue--) | Vrací nebo nastavuje odstín (hue) komponentu barvy v HSL reprezentaci. |
| [setHue(float value)](#setHue-float-) | Vrací nebo nastavuje odstín (hue) komponentu barvy v HSL reprezentaci. |
| [getSaturation()](#getSaturation--) | Vrací nebo nastavuje komponentu sytosti barvy v HSL reprezentaci. |
| [setSaturation(float value)](#setSaturation-float-) | Vrací nebo nastavuje komponentu sytosti barvy v HSL reprezentaci. |
| [getLuminance()](#getLuminance--) | Vrací nebo nastavuje komponentu jasu barvy v HSL reprezentaci. |
| [setLuminance(float value)](#setLuminance-float-) | Vrací nebo nastavuje komponentu jasu barvy v HSL reprezentaci. |
| [getColorTransform()](#getColorTransform--) | Vrací kolekci transformací barev aplikovaných na barvu. |
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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Vrací výslednou barvu (s aplikovanými všemi transformacemi barvy). Nastavuje RGB barvy a maže všechny transformace barvy. Čtení/zápis java.lang.Integer.

**Vrací:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Vrací výslednou barvu (s aplikovanými všemi transformacemi barvy). Nastavuje RGB barvy a maže všechny transformace barvy. Čtení/zápis java.lang.Integer.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Vrací nebo nastavuje předvolbu barvy. Čtení/zápis [PresetColor](../../com.aspose.slides/presetcolor).

**Vrací:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Vrací nebo nastavuje předvolbu barvy. Čtení/zápis [PresetColor](../../com.aspose.slides/presetcolor).

**Parametry:**
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Vrací nebo nastavuje barvu určenou barevným schématem. Čtení/zápis [SchemeColor](../../com.aspose.slides/schemecolor).

**Vrací:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Vrací nebo nastavuje barvu určenou barevným schématem. Čtení/zápis [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametry:**
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
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
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

Vrací nebo nastavuje odstín (hue) komponentu barvy v HSL reprezentaci. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Vrací:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Vrací nebo nastavuje odstín (hue) komponentu barvy v HSL reprezentaci. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Vrací nebo nastavuje komponentu sytosti barvy v HSL reprezentaci. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Vrací:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Vrací nebo nastavuje komponentu sytosti barvy v HSL reprezentaci. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Vrací nebo nastavuje komponentu jasu barvy v HSL reprezentaci. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Vrací:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Vrací nebo nastavuje komponentu jasu barvy v HSL reprezentaci. Všechny transformace barvy jsou ignorovány. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Vrací kolekci transformací barev aplikovaných na barvu. Pouze pro čtení [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Vrací:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Vrací řetězec, který představuje aktuální formát barvy.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| format | int | Typ řetězce formátu barvy. |

**Vrací:**
java.lang.String - řetězec, který představuje aktuální formát barvy.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Zkopíruje formát barvy z "color".

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Barva [IColorFormat](../../com.aspose.slides/icolorformat) |