---
title: IColorFormat
second_title: Aspose.Slides für Java API Referenz
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
| [getColorType()](#getColorType--) | Gibt die Farbdefinitionsmethode zurück oder legt sie fest. |
| [setColorType(int value)](#setColorType-int-) | Gibt die Farbdefinitionsmethode zurück oder legt sie fest. |
| [getColor()](#getColor--) | Gibt die resultierende Farbe zurück (mit allen angewendeten Farbumwandlungen). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Gibt die resultierende Farbe zurück (mit allen angewendeten Farbumwandlungen). |
| [getPresetColor()](#getPresetColor--) | Gibt die Farbvorgabe zurück oder legt sie fest. |
| [setPresetColor(int value)](#setPresetColor-int-) | Gibt die Farbvorgabe zurück oder legt sie fest. |
| [getSystemColor()](#getSystemColor--) | Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück oder legt sie fest. |
| [setSystemColor(int value)](#setSystemColor-int-) | Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück oder legt sie fest. |
| [getSchemeColor()](#getSchemeColor--) | Gibt die durch ein Farbschema identifizierte Farbe zurück oder legt sie fest. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Gibt die durch ein Farbschema identifizierte Farbe zurück oder legt sie fest. |
| [getR()](#getR--) | Gibt die rote Komponente einer Farbe zurück oder legt sie fest. |
| [setR(byte value)](#setR-byte-) | Gibt die rote Komponente einer Farbe zurück oder legt sie fest. |
| [getG()](#getG--) | Gibt die grüne Komponente einer Farbe zurück oder legt sie fest. |
| [setG(byte value)](#setG-byte-) | Gibt die grüne Komponente einer Farbe zurück oder legt sie fest. |
| [getB()](#getB--) | Gibt die blaue Komponente einer Farbe zurück oder legt sie fest. |
| [setB(byte value)](#setB-byte-) | Gibt die blaue Komponente einer Farbe zurück oder legt sie fest. |
| [getFloatR()](#getFloatR--) | Gibt die rote Komponente einer Farbe zurück oder legt sie fest. |
| [setFloatR(float value)](#setFloatR-float-) | Gibt die rote Komponente einer Farbe zurück oder legt sie fest. |
| [getFloatG()](#getFloatG--) | Gibt die grüne Komponente einer Farbe zurück oder legt sie fest. |
| [setFloatG(float value)](#setFloatG-float-) | Gibt die grüne Komponente einer Farbe zurück oder legt sie fest. |
| [getFloatB()](#getFloatB--) | Gibt die blaue Komponente einer Farbe zurück oder legt sie fest. |
| [setFloatB(float value)](#setFloatB-float-) | Gibt die blaue Komponente einer Farbe zurück oder legt sie fest. |
| [getHue()](#getHue--) | Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [setHue(float value)](#setHue-float-) | Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [getSaturation()](#getSaturation--) | Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [setSaturation(float value)](#setSaturation-float-) | Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [getLuminance()](#getLuminance--) | Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [setLuminance(float value)](#setLuminance-float-) | Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. |
| [getColorTransform()](#getColorTransform--) | Gibt die Sammlung von Farbumwandlungen zurück, die auf eine Farbe angewendet wurden. |
| [toString(int format)](#toString-int-) | Gibt einen String zurück, der das aktuelle Farbformat darstellt. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Kopiert das Farbformat von "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Gibt die Farbdefinitionsmethode zurück oder legt sie fest. Lese-/Schreib [ColorType](../../com.aspose.slides/colortype).

**Rückgabewert:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Gibt die Farbdefinitionsmethode zurück oder legt sie fest. Lese-/Schreib [ColorType](../../com.aspose.slides/colortype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getColor() {#getColor--}
```
public abstract Color getColor()
```

Gibt die resultierende Farbe zurück (mit allen angewendeten Farbumwandlungen). Setzt RGB-Farben und löscht alle Farbumwandlungen. Lese-/Schreib java.awt.Color.

**Rückgabewert:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Gibt die resultierende Farbe zurück (mit allen angewendeten Farbumwandlungen). Setzt RGB-Farben und löscht alle Farbumwandlungen. Lese-/Schreib java.awt.Color.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.awt.Color |  |
### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Gibt die Farbvorgabe zurück oder legt sie fest. Lese-/Schreib [PresetColor](../../com.aspose.slides/presetcolor).

**Rückgabewert:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Gibt die Farbvorgabe zurück oder legt sie fest. Lese-/Schreib [PresetColor](../../com.aspose.slides/presetcolor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück oder legt sie fest. Lese-/Schreib [SystemColor](../../com.aspose.slides/systemcolor).

**Rückgabewert:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Gibt die durch die Systemfarbtabelle identifizierte Farbe zurück oder legt sie fest. Lese-/Schreib [SystemColor](../../com.aspose.slides/systemcolor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Gibt die durch ein Farbschema identifizierte Farbe zurück oder legt sie fest. Lese-/Schreib [SchemeColor](../../com.aspose.slides/schemecolor).

**Rückgabewert:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Gibt die durch ein Farbschema identifizierte Farbe zurück oder legt sie fest. Lese-/Schreib [SchemeColor](../../com.aspose.slides/schemecolor).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | int |  |
### getR() {#getR--}
```
public abstract byte getR()
```

Gibt die rote Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib byte.

**Rückgabewert:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Gibt die rote Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getG() {#getG--}
```
public abstract byte getG()
```

Gibt die grüne Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib byte.

**Rückgabewert:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Gibt die grüne Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getB() {#getB--}
```
public abstract byte getB()
```

Gibt die blaue Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib byte.

**Rückgabewert:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Gibt die blaue Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib byte.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |
### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Gibt die rote Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Rückgabewert:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Gibt die rote Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Gibt die grüne Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Rückgabewert:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Gibt die grüne Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Gibt die blaue Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Rückgabewert:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Gibt die blaue Komponente einer Farbe zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getHue() {#getHue--}
```
public abstract float getHue()
```

Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Rückgabewert:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Gibt die Farbtonkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Rückgabewert:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Gibt die Sättigungskomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Rückgabewert:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Gibt die Luminanzkomponente einer Farbe in HSL-Darstellung zurück oder legt sie fest. Alle Farbumwandlungen werden ignoriert. Lese-/Schreib float.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | float |  |
### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Gibt die Sammlung von Farbumwandlungen zurück, die auf eine Farbe angewendet wurden. Nur lesen [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Rückgabewert:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Gibt einen String zurück, der das aktuelle Farbformat darstellt.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| format | int | Ein Typ des Farbzeichenfolgenformats. |

**Rückgabewert:**
java.lang.String - Eine Zeichenkette, die das aktuelle Farbformat darstellt.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Kopiert das Farbformat von "color".

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |