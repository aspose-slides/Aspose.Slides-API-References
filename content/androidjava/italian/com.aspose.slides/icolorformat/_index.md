---
title: IColorFormat
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta un colore utilizzato in una presentazione.
type: docs
url: /it/com.aspose.slides/icolorformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Rappresenta un colore utilizzato in una presentazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getColorType()](#getColorType--) | Restituisce o imposta il metodo di definizione del colore. |
| [setColorType(int value)](#setColorType-int-) | Restituisce o imposta il metodo di definizione del colore. |
| [getColor()](#getColor--) | Restituisce il colore risultante (con tutte le trasformazioni colore applicate). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Restituisce il colore risultante (con tutte le trasformazioni colore applicate). |
| [getPresetColor()](#getPresetColor--) | Restituisce o imposta il preset del colore. |
| [setPresetColor(int value)](#setPresetColor-int-) | Restituisce o imposta il preset del colore. |
| [getSystemColor()](#getSystemColor--) | Restituisce o imposta il colore identificato dalla tabella dei colori di sistema. |
| [setSystemColor(int value)](#setSystemColor-int-) | Restituisce o imposta il colore identificato dalla tabella dei colori di sistema. |
| [getSchemeColor()](#getSchemeColor--) | Restituisce o imposta il colore identificato da uno schema di colori. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Restituisce o imposta il colore identificato da uno schema di colori. |
| [getR()](#getR--) | Restituisce o imposta la componente rossa di un colore. |
| [setR(byte value)](#setR-byte-) | Restituisce o imposta la componente rossa di un colore. |
| [getG()](#getG--) | Restituisce o imposta la componente verde di un colore. |
| [setG(byte value)](#setG-byte-) | Restituisce o imposta la componente verde di un colore. |
| [getB()](#getB--) | Restituisce o imposta la componente blu di un colore. |
| [setB(byte value)](#setB-byte-) | Restituisce o imposta la componente blu di un colore. |
| [getFloatR()](#getFloatR--) | Restituisce o imposta la componente rossa di un colore. |
| [setFloatR(float value)](#setFloatR-float-) | Restituisce o imposta la componente rossa di un colore. |
| [getFloatG()](#getFloatG--) | Restituisce o imposta la componente verde di un colore. |
| [setFloatG(float value)](#setFloatG-float-) | Restituisce o imposta la componente verde di un colore. |
| [getFloatB()](#getFloatB--) | Restituisce o imposta la componente blu di un colore. |
| [setFloatB(float value)](#setFloatB-float-) | Restituisce o imposta la componente blu di un colore. |
| [getHue()](#getHue--) | Restituisce o imposta la componente tonalità di un colore in rappresentazione HSL. |
| [setHue(float value)](#setHue-float-) | Restituisce o imposta la componente tonalità di un colore in rappresentazione HSL. |
| [getSaturation()](#getSaturation--) | Restituisce o imposta la componente saturazione di un colore in rappresentazione HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Restituisce o imposta la componente saturazione di un colore in rappresentazione HSL. |
| [getLuminance()](#getLuminance--) | Restituisce o imposta la componente luminanza di un colore in rappresentazione HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Restituisce o imposta la componente luminanza di un colore in rappresentazione HSL. |
| [getColorTransform()](#getColorTransform--) | Restituisce la collezione di trasformazioni colore applicate a un colore. |
| [toString(int format)](#toString-int-) | Restituisce una String che rappresenta il formato colore corrente. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Copia il formato colore da "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```


Restituisce o imposta il metodo di definizione del colore. Lettura/scrittura [ColorType](../../com.aspose.slides/colortype).

**Restituisce:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```


Restituisce o imposta il metodo di definizione del colore. Lettura/scrittura [ColorType](../../com.aspose.slides/colortype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```


Restituisce il colore risultante (con tutte le trasformazioni colore applicate). Imposta i colori RGB e cancella tutte le trasformazioni colore. Lettura/scrittura java.lang.Integer.

**Restituisce:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


Restituisce il colore risultante (con tutte le trasformazioni colore applicate). Imposta i colori RGB e cancella tutte le trasformazioni colore. Lettura/scrittura java.lang.Integer.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```


Restituisce o imposta il preset del colore. Lettura/scrittura [PresetColor](../../com.aspose.slides/presetcolor).

**Restituisce:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```


Restituisce o imposta il preset del colore. Lettura/scrittura [PresetColor](../../com.aspose.slides/presetcolor).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```


Restituisce o imposta il colore identificato dalla tabella dei colori di sistema. Lettura/scrittura [SystemColor](../../com.aspose.slides/systemcolor).

**Restituisce:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```


Restituisce o imposta il colore identificato dalla tabella dei colori di sistema. Lettura/scrittura [SystemColor](../../com.aspose.slides/systemcolor).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```


Restituisce o imposta il colore identificato da uno schema di colori. Lettura/scrittura [SchemeColor](../../com.aspose.slides/schemecolor).

**Restituisce:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```


Restituisce o imposta il colore identificato da uno schema di colori. Lettura/scrittura [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```


Restituisce o imposta la componente rossa di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura byte.

**Restituisce:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```


Restituisce o imposta la componente rossa di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```


Restituisce o imposta la componente verde di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura byte.

**Restituisce:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```


Restituisce o imposta la componente verde di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```


Restituisce o imposta la componente blu di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura byte.

**Restituisce:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```


Restituisce o imposta la componente blu di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura byte.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```


Restituisce o imposta la componente rossa di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Restituisce:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```


Restituisce o imposta la componente rossa di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```


Restituisce o imposta la componente verde di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Restituisce:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```


Restituisce o imposta la componente verde di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```


Restituisce o imposta la componente blu di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Restituisce:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```


Restituisce o imposta la componente blu di un colore. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```


Restituisce o imposta la componente tonalità di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Restituisce:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```


Restituisce o imposta la componente tonalità di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```


Restituisce o imposta la componente saturazione di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Restituisce:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```


Restituisce o imposta la componente saturazione di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```


Restituisce o imposta la componente luminanza di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Restituisce:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```


Restituisce o imposta la componente luminanza di un colore in rappresentazione HSL. Tutte le trasformazioni colore sono ignorate. Lettura/scrittura float.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```


Restituisce la collezione di trasformazioni colore applicate a un colore. Solo lettura [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Restituisce:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```


Restituisce una String che rappresenta il formato colore corrente.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| format | int | Un tipo di formato stringa colore. |

**Restituisce:**
java.lang.String - Una stringa che rappresenta il formato colore corrente.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```


Copia il formato colore da "color".

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |