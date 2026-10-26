---
title: IColorFormat
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een kleur voor die in een presentatie wordt gebruikt.
type: docs
url: /nl/com.aspose.slides/icolorformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Stelt een kleur voor die in een presentatie wordt gebruikt.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getColorType()](#getColorType--) | Retourneert of stelt de kleurdefinitie-methode in. |
| [setColorType(int value)](#setColorType-int-) | Retourneert of stelt de kleurdefinitie-methode in. |
| [getColor()](#getColor--) | Retourneert de resulterende kleur (met alle kleurtransformaties toegepast). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Retourneert de resulterende kleur (met alle kleurtransformaties toegepast). |
| [getPresetColor()](#getPresetColor--) | Retourneert of stelt de kleurpreset in. |
| [setPresetColor(int value)](#setPresetColor-int-) | Retourneert of stelt de kleurpreset in. |
| [getSystemColor()](#getSystemColor--) | Retourneert of stelt de kleur geïdentificeerd door de systeemtabel voor kleuren in. |
| [setSystemColor(int value)](#setSystemColor-int-) | Retourneert of stelt de kleur geïdentificeerd door de systeemtabel voor kleuren in. |
| [getSchemeColor()](#getSchemeColor--) | Retourneert of stelt de kleur geïdentificeerd door een kleurschema in. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Retourneert of stelt de kleur geïdentificeerd door een kleurschema in. |
| [getR()](#getR--) | Retourneert of stelt de rode component van een kleur in. |
| [setR(byte value)](#setR-byte-) | Retourneert of stelt de rode component van een kleur in. |
| [getG()](#getG--) | Retourneert of stelt de groene component van een kleur in. |
| [setG(byte value)](#setG-byte-) | Retourneert of stelt de groene component van een kleur in. |
| [getB()](#getB--) | Retourneert of stelt de blauwe component van een kleur in. |
| [setB(byte value)](#setB-byte-) | Retourneert of stelt de blauwe component van een kleur in. |
| [getFloatR()](#getFloatR--) | Retourneert of stelt de rode component van een kleur in. |
| [setFloatR(float value)](#setFloatR-float-) | Retourneert of stelt de rode component van een kleur in. |
| [getFloatG()](#getFloatG--) | Retourneert of stelt de groene component van een kleur in. |
| [setFloatG(float value)](#setFloatG-float-) | Retourneert of stelt de groene component van een kleur in. |
| [getFloatB()](#getFloatB--) | Retourneert of stelt de blauwe component van een kleur in. |
| [setFloatB(float value)](#setFloatB-float-) | Retourneert of stelt de blauwe component van een kleur in. |
| [getHue()](#getHue--) | Retourneert of stelt de tintcomponent van een kleur in HSL-representatie in. |
| [setHue(float value)](#setHue-float-) | Retourneert of stelt de tintcomponent van een kleur in HSL-representatie in. |
| [getSaturation()](#getSaturation--) | Retourneert of stelt de verzadigingscomponent van een kleur in HSL-representatie in. |
| [setSaturation(float value)](#setSaturation-float-) | Retourneert of stelt de verzadigingscomponent van een kleur in HSL-representatie in. |
| [getLuminance()](#getLuminance--) | Retourneert of stelt de luminantiecomponent van een kleur in HSL-representatie in. |
| [setLuminance(float value)](#setLuminance-float-) | Retourneert of stelt de luminantiecomponent van een kleur in HSL-representatie in. |
| [getColorTransform()](#getColorTransform--) | Retourneert de verzameling kleurtransformaties die op een kleur worden toegepast. |
| [toString(int format)](#toString-int-) | Retourneert een String die het huidige kleurformaat weergeeft. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Kopieer kleurformaat van "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```


Retourneert of stelt de kleurdefinitie-methode in. Lezen/schrijven [ColorType](../../com.aspose.slides/colortype).

**Retour:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```


Retourneert of stelt de kleurdefinitie-methode in. Lezen/schrijven [ColorType](../../com.aspose.slides/colortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


Retourneert de resulterende kleur (met alle kleurtransformaties toegepast). Stelt RGB-kleuren in en wist alle kleurtransformaties. Lezen/schrijven java.awt.Color.

**Retour:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Retourneert de resulterende kleur (met alle kleurtransformaties toegepast). Stelt RGB-kleuren in en wist alle kleurtransformaties. Lezen/schrijven java.awt.Color.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```


Retourneert of stelt de kleurpreset in. Lezen/schrijven [PresetColor](../../com.aspose.slides/presetcolor).

**Retour:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```


Retourneert of stelt de kleurpreset in. Lezen/schrijven [PresetColor](../../com.aspose.slides/presetcolor).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```


Retourneert of stelt de kleur geïdentificeerd door de systeemtabel voor kleuren in. Lezen/schrijven [SystemColor](../../com.aspose.slides/systemcolor).

**Retour:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```


Retourneert of stelt de kleur geïdentificeerd door de systeemtabel voor kleuren in. Lezen/schrijven [SystemColor](../../com.aspose.slides/systemcolor).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```


Retourneert of stelt de kleur geïdentificeerd door een kleurschema in. Lezen/schrijven [SchemeColor](../../com.aspose.slides/schemecolor).

**Retour:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```


Retourneert of stelt de kleur geïdentificeerd door een kleurschema in. Lezen/schrijven [SchemeColor](../../com.aspose.slides/schemecolor).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```


Retourneert of stelt de rode component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Retour:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```


Retourneert of stelt de rode component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```


Retourneert of stelt de groene component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Retour:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```


Retourneert of stelt de groene component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```


Retourneert of stelt de blauwe component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Retour:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```


Retourneert of stelt de blauwe component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```


Retourneert of stelt de rode component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```


Retourneert of stelt de rode component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```


Retourneert of stelt de groene component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```


Retourneert of stelt de groene component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```


Retourneert of stelt de blauwe component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```


Retourneert of stelt de blauwe component van een kleur in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```


Retourneert of stelt de tintcomponent van een kleur in HSL-representatie in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```


Retourneert of stelt de tintcomponent van een kleur in HSL-representatie in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```


Retourneert of stelt de verzadigingscomponent van een kleur in HSL-representatie in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```


Retourneert of stelt de verzadigingscomponent van een kleur in HSL-representatie in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```


Retourneert of stelt de luminantiecomponent van een kleur in HSL-representatie in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```


Retourneert of stelt de luminantiecomponent van een kleur in HSL-representatie in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```


Retourneert de verzameling kleurtransformaties die op een kleur worden toegepast. Alleen-lezen [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Retour:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```


Retourneert een String die het huidige kleurformaat weergeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | int | Een type kleur-stringformaat. |

**Retour:**
java.lang.String - Een string die het huidige kleurformaat weergeeft.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```


Kopieer kleurformaat van "color".

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Kleur [IColorFormat](../../com.aspose.slides/icolorformat) |