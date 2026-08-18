---
title: IColorFormat
second_title: Aspose.Slides dla Java - odniesienie API
description: Reprezentuje kolor używany w prezentacji.
type: docs
url: /pl/com.aspose.slides/icolorformat/
---
**All Implemented Interfaces:**
[com.aspose.slides.IFillParamSource](../../com.aspose.slides/ifillparamsource)
```
public interface IColorFormat extends IFillParamSource
```

Reprezentuje kolor używany w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getColorType()](#getColorType--) | Zwraca lub ustawia metodę definiowania koloru. |
| [setColorType(int value)](#setColorType-int-) | Zwraca lub ustawia metodę definiowania koloru. |
| [getColor()](#getColor--) | Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami kolorów). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami kolorów). |
| [getPresetColor()](#getPresetColor--) | Zwraca lub ustawia predefiniowany kolor. |
| [setPresetColor(int value)](#setPresetColor-int-) | Zwraca lub ustawia predefiniowany kolor. |
| [getSystemColor()](#getSystemColor--) | Zwraca lub ustawia kolor zidentyfikowany w systemowej tabeli kolorów. |
| [setSystemColor(int value)](#setSystemColor-int-) | Zwraca lub ustawia kolor zidentyfikowany w systemowej tabeli kolorów. |
| [getSchemeColor()](#getSchemeColor--) | Zwraca lub ustawia kolor zidentyfikowany w schemacie kolorów. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Zwraca lub ustawia kolor zidentyfikowany w schemacie kolorów. |
| [getR()](#getR--) | Zwraca lub ustawia komponent czerwony koloru. |
| [setR(byte value)](#setR-byte-) | Zwraca lub ustawia komponent czerwony koloru. |
| [getG()](#getG--) | Zwraca lub ustawia komponent zielony koloru. |
| [setG(byte value)](#setG-byte-) | Zwraca lub ustawia komponent zielony koloru. |
| [getB()](#getB--) | Zwraca lub ustawia komponent niebieski koloru. |
| [setB(byte value)](#setB-byte-) | Zwraca lub ustawia komponent niebieski koloru. |
| [getFloatR()](#getFloatR--) | Zwraca lub ustawia komponent czerwony koloru. |
| [setFloatR(float value)](#setFloatR-float-) | Zwraca lub ustawia komponent czerwony koloru. |
| [getFloatG()](#getFloatG--) | Zwraca lub ustawia komponent zielony koloru. |
| [setFloatG(float value)](#setFloatG-float-) | Zwraca lub ustawia komponent zielony koloru. |
| [getFloatB()](#getFloatB--) | Zwraca lub ustawia komponent niebieski koloru. |
| [setFloatB(float value)](#setFloatB-float-) | Zwraca lub ustawia komponent niebieski koloru. |
| [getHue()](#getHue--) | Zwraca lub ustawia komponent odcienia koloru w reprezentacji HSL. |
| [setHue(float value)](#setHue-float-) | Zwraca lub ustawia komponent odcienia koloru w reprezentacji HSL. |
| [getSaturation()](#getSaturation--) | Zwraca lub ustawia komponent nasycenia koloru w reprezentacji HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Zwraca lub ustawia komponent nasycenia koloru w reprezentacji HSL. |
| [getLuminance()](#getLuminance--) | Zwraca lub ustawia komponent luminancji koloru w reprezentacji HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Zwraca lub ustawia komponent luminancji koloru w reprezentacji HSL. |
| [getColorTransform()](#getColorTransform--) | Zwraca kolekcję transformacji kolorów zastosowanych do koloru. |
| [toString(int format)](#toString-int-) | Zwraca łańcuch znaków reprezentujący bieżący format koloru. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Skopiuj format koloru z "color". |
### getColorType() {#getColorType--}
```
public abstract int getColorType()
```

Zwraca lub ustawia metodę definiowania koloru. Odczyt/zapis [ColorType](../../com.aspose.slides/colortype).

**Zwraca:**
int
### setColorType(int value) {#setColorType-int-}
```
public abstract void setColorType(int value)
```

Zwraca lub ustawia metodę definiowania koloru. Odczyt/zapis [ColorType](../../com.aspose.slides/colortype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```

Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami kolorów). Ustawia kolory RGB i usuwa wszystkie transformacje kolorów. Odczyt/zapis java.awt.Color.

**Zwraca:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```

Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami kolorów). Ustawia kolory RGB i usuwa wszystkie transformacje kolorów. Odczyt/zapis java.awt.Color.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Zwraca lub ustawia predefiniowany kolor. Odczyt/zapis [PresetColor](../../com.aspose.slides/presetcolor).

**Zwraca:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Zwraca lub ustawia predefiniowany kolor. Odczyt/zapis [PresetColor](../../com.aspose.slides/presetcolor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Zwraca lub ustawia kolor zidentyfikowany w systemowej tabeli kolorów. Odczyt/zapis [SystemColor](../../com.aspose.slides/systemcolor).

**Zwraca:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Zwraca lub ustawia kolor zidentyfikowany w systemowej tabeli kolorów. Odczyt/zapis [SystemColor](../../com.aspose.slides/systemcolor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Zwraca lub ustawia kolor zidentyfikowany w schemacie kolorów. Odczyt/zapis [SchemeColor](../../com.aspose.slides/schemecolor).

**Zwraca:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Zwraca lub ustawia kolor zidentyfikowany w schemacie kolorów. Odczyt/zapis [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Zwraca lub ustawia komponent czerwony koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis byte.

**Zwraca:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Zwraca lub ustawia komponent czerwony koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Zwraca lub ustawia komponent zielony koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis byte.

**Zwraca:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Zwraca lub ustawia komponent zielony koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Zwraca lub ustawia komponent niebieski koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis byte.

**Zwraca:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Zwraca lub ustawia komponent niebieski koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Zwraca lub ustawia komponent czerwony koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Zwraca lub ustawia komponent czerwony koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Zwraca lub ustawia komponent zielony koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Zwraca lub ustawia komponent zielony koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Zwraca lub ustawia komponent niebieski koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Zwraca lub ustawia komponent niebieski koloru. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Zwraca lub ustawia komponent odcienia koloru w reprezentacji HSL. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Zwraca lub ustawia komponent odcienia koloru w reprezentacji HSL. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Zwraca lub ustawia komponent nasycenia koloru w reprezentacji HSL. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Zwraca lub ustawia komponent nasycenia koloru w reprezentacji HSL. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Zwraca lub ustawia komponent luminancji koloru w reprezentacji HSL. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Zwraca lub ustawia komponent luminancji koloru w reprezentacji HSL. Wszystkie transformacje kolorów są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Zwraca kolekcję transformacji kolorów zastosowanych do koloru. Tylko do odczytu [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Zwraca:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Zwraca łańcuch znaków reprezentujący bieżący format koloru.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| format | int | Typ formatu łańcucha znaków koloru. |

**Zwraca:**
java.lang.String - Łańcuch znaków reprezentujący bieżący format koloru.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Skopiuj format koloru z "color".

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Color [IColorFormat](../../com.aspose.slides/icolorformat) |
