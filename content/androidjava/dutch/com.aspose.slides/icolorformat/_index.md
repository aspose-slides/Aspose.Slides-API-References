---
title: IColorFormat
second_title: Aspose.Slides voor Android via Java API-referentie
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
| [getColorType()](#getColorType--) | Geeft de kleurdefinitiemethode terug of stelt deze in. |
| [setColorType(int value)](#setColorType-int-) | Geeft de kleurdefinitiemethode terug of stelt deze in. |
| [getColor()](#getColor--) | Geeft de resulterende kleur terug (met alle kleurtransformaties toegepast). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Geeft de resulterende kleur terug (met alle kleurtransformaties toegepast). |
| [getPresetColor()](#getPresetColor--) | Geeft de vooraf ingestelde kleur terug of stelt deze in. |
| [setPresetColor(int value)](#setPresetColor-int-) | Geeft de vooraf ingestelde kleur terug of stelt deze in. |
| [getSystemColor()](#getSystemColor--) | Geeft de kleur terug die wordt geïdentificeerd door de systeemtabel voor kleuren of stelt deze in. |
| [setSystemColor(int value)](#setSystemColor-int-) | Geeft de kleur terug die wordt geïdentificeerd door de systeemtabel voor kleuren of stelt deze in. |
| [getSchemeColor()](#getSchemeColor--) | Geeft de kleur terug die wordt geïdentificeerd door een kleurenpalet of stelt deze in. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Geeft de kleur terug die wordt geïdentificeerd door een kleurenpalet of stelt deze in. |
| [getR()](#getR--) | Geeft de rode component van een kleur terug of stelt deze in. |
| [setR(byte value)](#setR-byte-) | Geeft de rode component van een kleur terug of stelt deze in. |
| [getG()](#getG--) | Geeft de groene component van een kleur terug of stelt deze in. |
| [setG(byte value)](#setG-byte-) | Geeft de groene component van een kleur terug of stelt deze in. |
| [getB()](#getB--) | Geeft de blauwe component van een kleur terug of stelt deze in. |
| [setB(byte value)](#setB-byte-) | Geeft de blauwe component van een kleur terug of stelt deze in. |
| [getFloatR()](#getFloatR--) | Geeft de rode component van een kleur terug of stelt deze in. |
| [setFloatR(float value)](#setFloatR-float-) | Geeft de rode component van een kleur terug of stelt deze in. |
| [getFloatG()](#getFloatG--) | Geeft de groene component van een kleur terug of stelt deze in. |
| [setFloatG(float value)](#setFloatG-float-) | Geeft de groene component van een kleur terug of stelt deze in. |
| [getFloatB()](#getFloatB--) | Geeft de blauwe component van een kleur terug of stelt deze in. |
| [setFloatB(float value)](#setFloatB-float-) | Geeft de blauwe component van een kleur terug of stelt deze in. |
| [getHue()](#getHue--) | Geeft de tintcomponent van een kleur in HSL-representatie terug of stelt deze in. |
| [setHue(float value)](#setHue-float-) | Geeft de tintcomponent van een kleur in HSL-representatie terug of stelt deze in. |
| [getSaturation()](#getSaturation--) | Geeft de verzadigingscomponent van een kleur in HSL-representatie terug of stelt deze in. |
| [setSaturation(float value)](#setSaturation-float-) | Geeft de verzadigingscomponent van een kleur in HSL-representatie terug of stelt deze in. |
| [getLuminance()](#getLuminance--) | Geeft de luminantiecomponent van een kleur in HSL-representatie terug of stelt deze in. |
| [setLuminance(float value)](#setLuminance-float-) | Geeft de luminantiecomponent van een kleur in HSL-representatie terug of stelt deze in. |
| [getColorTransform()](#getColorTransform--) | Geeft de verzameling van kleurtransformaties die op een kleur zijn toegepast terug. |
| [toString(int format)](#toString-int-) | Geeft een String terug die het huidige kleurformaat weergeeft. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Kopieer kleurformaat van "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```


Geeft de kleurdefinitiemethode terug of stelt deze in. Lezen/schrijven [ColorType](../../com.aspose.slides/colortype).

**Retour:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```


Geeft de kleurdefinitiemethode terug of stelt deze in. Lezen/schrijven [ColorType](../../com.aspose.slides/colortype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Integer getColor()
```


Geeft de resulterende kleur terug (met alle kleurtransformaties toegepast). Stelt RGB-kleuren in en wist alle kleurtransformaties. Lezen/schrijven java.lang.Integer.

**Retour:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```


Geeft de resulterende kleur terug (met alle kleurtransformaties toegepast). Stelt RGB-kleuren in en wist alle kleurtransformaties. Lezen/schrijven java.lang.Integer.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```


Geeft de vooraf ingestelde kleur terug of stelt deze in. Lezen/schrijven [PresetColor](../../com.aspose.slides/presetcolor).

**Retour:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```


Geeft de vooraf ingestelde kleur terug of stelt deze in. Lezen/schrijven [PresetColor](../../com.aspose.slides/presetcolor).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```


Geeft de kleur terug die wordt geïdentificeerd door de systeemtabel voor kleuren of stelt deze in. Lezen/schrijven [SystemColor](../../com.aspose.slides/systemcolor).

**Retour:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```


Geeft de kleur terug die wordt geïdentificeerd door de systeemtabel voor kleuren of stelt deze in. Lezen/schrijven [SystemColor](../../com.aspose.slides/systemcolor).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```


Geeft de kleur terug die wordt geïdentificeerd door een kleurenpalet of stelt deze in. Lezen/schrijven [SchemeColor](../../com.aspose.slides/schemecolor).

**Retour:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```


Geeft de kleur terug die wordt geïdentificeerd door een kleurenpalet of stelt deze in. Lezen/schrijven [SchemeColor](../../com.aspose.slides/schemecolor).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```


Geeft de rode component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Retour:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```


Geeft de rode component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```


Geeft de groene component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Retour:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```


Geeft de groene component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```


Geeft de blauwe component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Retour:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```


Geeft de blauwe component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven byte.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```


Geeft de rode component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```


Geeft de rode component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```


Geeft de groene component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```


Geeft de groene component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```


Geeft de blauwe component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```


Geeft de blauwe component van een kleur terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```


Geeft de tintcomponent van een kleur in HSL-representatie terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```


Geeft de tintcomponent van een kleur in HSL-representatie terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```


Geeft de verzadigingscomponent van een kleur in HSL-representatie terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```


Geeft de verzadigingscomponent van een kleur in HSL-representatie terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```


Geeft de luminantiecomponent van een kleur in HSL-representatie terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Retour:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```


Geeft de luminantiecomponent van een kleur in HSL-representatie terug of stelt deze in. Alle kleurtransformaties worden genegeerd. Lezen/schrijven float.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```


Geeft de verzameling van kleurtransformaties die op een kleur zijn toegepast terug. Alleen-lezen [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Retour:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```


Geeft een String terug die het huidige kleurformaat weergeeft.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| format | int | Een type van kleur-stringformaat. |

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