---
title: IColorFormat
second_title: Aspose.Slides für Android über Java-API-Referenz
description: Stellt eine in einer Präsentation verwendete Farbe dar.
type: docs
url: /de/com.aspose.slides/icolorformat/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Stellt eine in einer Präsentation verwendete Farbe dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getColorType()](#getColorType--) | Gibt die Farbbestimmungsmethode zurück oder setzt sie. |
| [setColorType(int value)](#setColorType-int-) | Gibt die Farbbestimmungsmethode zurück oder setzt sie. |
| [getColor()](#getColor--) | Gibt die resultierende Farbe zurück (mit allen angewendeten Farbtransformationen). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Gibt die resultierende Farbe zurück (mit allen angewendeten Farbtransformationen). |
| [getPresetColor()](#getPresetColor--) | Gibt die Farbvorgabe zurück oder setzt sie. |
| [setPresetColor(int value)](#setPresetColor-int-) | Gibt die Farbvorgabe zurück oder setzt sie. |
| [getSystemColor()](#getSystemColor--) | Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück oder setzt sie. |
| [setSystemColor(int value)](#setSystemColor-int-) | Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück oder setzt sie. |
| [getSchemeColor()](#getSchemeColor--) | Gibt die durch ein Farbschema identifizierte Farbe zurück oder setzt sie. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Gibt die durch ein Farbschema identifizierte Farbe zurück oder setzt sie. |
| [getR()](#getR--) | Gibt den Rotanteil einer Farbe zurück oder setzt ihn. |
| [setR(byte value)](#setR-byte-) | Gibt den Rotanteil einer Farbe zurück oder setzt ihn. |
| [getG()](#getG--) | Gibt den Grünanteil einer Farbe zurück oder setzt ihn. |
| [setG(byte value)](#setG-byte-) | Gibt den Grünanteil einer Farbe zurück oder setzt ihn. |
| [getB()](#getB--) | Gibt den Blauanteil einer Farbe zurück oder setzt ihn. |
| [setB(byte value)](#setB-byte-) | Gibt den Blauanteil einer Farbe zurück oder setzt ihn. |
| [getFloatR()](#getFloatR--) | Gibt den Rotanteil einer Farbe zurück oder setzt ihn. |
| [setFloatR(float value)](#setFloatR-float-) | Gibt den Rotanteil einer Farbe zurück oder setzt ihn. |
| [getFloatG()](#getFloatG--) | Gibt den Grünanteil einer Farbe zurück oder setzt ihn. |
| [setFloatG(float value)](#setFloatG-float-) | Gibt den Grünanteil einer Farbe zurück oder setzt ihn. |
| [getFloatB()](#getFloatB--) | Gibt den Blauanteil einer Farbe zurück oder setzt ihn. |
| [setFloatB(float value)](#setFloatB-float-) | Gibt den Blauanteil einer Farbe zurück oder setzt ihn. |
| [getHue()](#getHue--) | Gibt den Farbtonanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. |
| [setHue(float value)](#setHue-float-) | Gibt den Farbtonanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. |
| [getSaturation()](#getSaturation--) | Gibt den Sättigungsanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. |
| [setSaturation(float value)](#setSaturation-float-) | Gibt den Sättigungsanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. |
| [getLuminance()](#getLuminance--) | Gibt den Luminanzanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. |
| [setLuminance(float value)](#setLuminance-float-) | Gibt den Luminanzanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. |
| [getColorTransform()](#getColorTransform--) | Gibt die Sammlung von Farbtransformationen zurück, die auf eine Farbe angewendet wurden. |
| [toString(int format)](#toString-int-) | Gibt einen String zurück, der das aktuelle Farbformat darstellt. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Kopiert das Farbformat von "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Gibt die Farbbestimmungsmethode zurück oder setzt sie. **Lesen/Schreiben** [ColorType](../../com.aspose.slides/colortype).

**Rückgabe:**  
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Gibt die Farbbestimmungsmethode zurück oder setzt sie. **Lesen/Schreiben** [ColorType](../../com.aspose.slides/colortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Integer getColor()
```

Gibt die resultierende Farbe zurück (mit allen angewendeten Farbtransformationen). Setzt RGB-Farben und löscht alle Farbtransformationen. **Lesen/Schreiben** java.lang.Integer.

**Rückgabe:**  
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Gibt die resultierende Farbe zurück (mit allen angewendeten Farbtransformationen). Setzt RGB-Farben und löscht alle Farbtransformationen. **Lesen/Schreiben** java.lang.Integer.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.Integer |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Gibt die Farbvorgabe zurück oder setzt sie. **Lesen/Schreiben** [PresetColor](../../com.aspose.slides/presetcolor).

**Rückgabe:**  
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Gibt die Farbvorgabe zurück oder setzt sie. **Lesen/Schreiben** [PresetColor](../../com.aspose.slides/presetcolor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück oder setzt sie. **Lesen/Schreiben** [SystemColor](../../com.aspose.slides/systemcolor).

**Rückgabe:**  
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück oder setzt sie. **Lesen/Schreiben** [SystemColor](../../com.aspose.slides/systemcolor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Gibt die durch ein Farbschema identifizierte Farbe zurück oder setzt sie. **Lesen/Schreiben** [SchemeColor](../../com.aspose.slides/schemecolor).

**Rückgabe:**  
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Gibt die durch ein Farbschema identifizierte Farbe zurück oder setzt sie. **Lesen/Schreiben** [SchemeColor](../../com.aspose.slides/schemecolor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

Gibt den Rotanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** byte.

**Rückgabe:**  
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Gibt den Rotanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

Gibt den Grünanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** byte.

**Rückgabe:**  
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Gibt den Grünanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

Gibt den Blauanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** byte.

**Rückgabe:**  
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Gibt den Blauanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Gibt den Rotanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Rückgabe:**  
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Gibt den Rotanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Gibt den Grünanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Rückgabe:**  
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Gibt den Grünanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Gibt den Blauanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Rückgabe:**  
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Gibt den Blauanteil einer Farbe zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

Gibt den Farbtonanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Rückgabe:**  
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Gibt den Farbtonanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Gibt den Sättigungsanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Rückgabe:**  
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Gibt den Sättigungsanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Gibt den Luminanzanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Rückgabe:**  
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Gibt den Luminanzanteil einer Farbe in HSL-Darstellung zurück oder setzt ihn. Alle Farbtransformationen werden ignoriert. **Lesen/Schreiben** float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Gibt die Sammlung von Farbtransformationen zurück, die auf eine Farbe angewendet wurden. **Nur lesend** [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Rückgabe:**  
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Gibt einen String zurück, der das aktuelle Farbformat darstellt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | int | Ein Typ des Farbstring-Formats. |

**Rückgabe:**  
java.lang.String - Eine Zeichenkette, die das aktuelle Farbformat darstellt.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Kopiert das Farbformat von "color".

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Farbe [IColorFormat](../../com.aspose.slides/icolorformat) |