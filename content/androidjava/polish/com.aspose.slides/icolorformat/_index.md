---
title: IColorFormat
second_title: Aspose.Slides dla Androida – odniesienie API Java
description: Reprezentuje kolor używany w prezentacji.
type: docs
url: /pl/com.aspose.slides/icolorformat/
---
**Wszystkie zaimplementowane interfejsy:**
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
| [getColor()](#getColor--) | Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). |
| [setColor(Integer value)](#setColor-java.lang.Integer-) | Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). |
| [getPresetColor()](#getPresetColor--) | Zwraca lub ustawia domyślny kolor. |
| [setPresetColor(int value)](#setPresetColor-int-) | Zwraca lub ustawia domyślny kolor. |
| [getSystemColor()](#getSystemColor--) | Zwraca lub ustawia kolor określony w tabeli kolorów systemu. |
| [setSystemColor(int value)](#setSystemColor-int-) | Zwraca lub ustawia kolor określony w tabeli kolorów systemu. |
| [getSchemeColor()](#getSchemeColor--) | Zwraca lub ustawia kolor określony w schemacie kolorów. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Zwraca lub ustawia kolor określony w schemacie kolorów. |
| [getR()](#getR--) | Zwraca lub ustawia komponentę czerwieni koloru. |
| [setR(byte value)](#setR-byte-) | Zwraca lub ustawia komponentę czerwieni koloru. |
| [getG()](#getG--) | Zwraca lub ustawia komponentę zieleni koloru. |
| [setG(byte value)](#setG-byte-) | Zwraca lub ustawia komponentę zieleni koloru. |
| [getB()](#getB--) | Zwraca lub ustawia komponentę niebieskiego koloru. |
| [setB(byte value)](#setB-byte-) | Zwraca lub ustawia komponentę niebieskiego koloru. |
| [getFloatR()](#getFloatR--) | Zwraca lub ustawia komponentę czerwieni koloru. |
| [setFloatR(float value)](#setFloatR-float-) | Zwraca lub ustawia komponentę czerwieni koloru. |
| [getFloatG()](#getFloatG--) | Zwraca lub ustawia komponentę zieleni koloru. |
| [setFloatG(float value)](#setFloatG-float-) | Zwraca lub ustawia komponentę zieleni koloru. |
| [getFloatB()](#getFloatB--) | Zwraca lub ustawia komponentę niebieskiego koloru. |
| [setFloatB(float value)](#setFloatB-float-) | Zwraca lub ustawia komponentę niebieskiego koloru. |
| [getHue()](#getHue--) | Zwraca lub ustawia komponentę odcienia koloru w reprezentacji HSL. |
| [setHue(float value)](#setHue-float-) | Zwraca lub ustawia komponentę odcienia koloru w reprezentacji HSL. |
| [getSaturation()](#getSaturation--) | Zwraca lub ustawia komponentę nasycenia koloru w reprezentacji HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Zwraca lub ustawia komponentę nasycenia koloru w reprezentacji HSL. |
| [getLuminance()](#getLuminance--) | Zwraca lub ustawia komponentę luminancji koloru w reprezentacji HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Zwraca lub ustawia komponentę luminancji koloru w reprezentacji HSL. |
| [getColorTransform()](#getColorTransform--) | Zwraca kolekcję transformacji koloru zastosowanych do koloru. |
| [toString(int format)](#toString-int-) | Zwraca String, który reprezentuje aktualny format koloru. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Kopiuj format koloru z „color”. |
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
public abstract Integer getColor()
```

Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). Ustawia kolory RGB i usuwa wszystkie transformacje koloru. Odczyt/zapis java.lang.Integer.

**Zwraca:**
java.lang.Integer
### setColor(Integer value) {#setColor-java.lang.Integer-}
```
public abstract void setColor(Integer value)
```

Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). Ustawia kolory RGB i usuwa wszystkie transformacje koloru. Odczyt/zapis java.lang.Integer.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.Integer |  |

### getPresetColor() {#getPresetColor--}
```
public abstract int getPresetColor()
```

Zwraca lub ustawia domyślny kolor. Odczyt/zapis [PresetColor](../../com.aspose.slides/presetcolor).

**Zwraca:**
int
### setPresetColor(int value) {#setPresetColor-int-}
```
public abstract void setPresetColor(int value)
```

Zwraca lub ustawia domyślny kolor. Odczyt/zapis [PresetColor](../../com.aspose.slides/presetcolor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public abstract int getSystemColor()
```

Zwraca lub ustawia kolor określony w tabeli kolorów systemu. Odczyt/zapis [SystemColor](../../com.aspose.slides/systemcolor).

**Zwraca:**
int
### setSystemColor(int value) {#setSystemColor-int-}
```
public abstract void setSystemColor(int value)
```

Zwraca lub ustawia kolor określony w tabeli kolorów systemu. Odczyt/zapis [SystemColor](../../com.aspose.slides/systemcolor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public abstract int getSchemeColor()
```

Zwraca lub ustawia kolor określony w schemacie kolorów. Odczyt/zapis [SchemeColor](../../com.aspose.slides/schemecolor).

**Zwraca:**
int
### setSchemeColor(int value) {#setSchemeColor-int-}
```
public abstract void setSchemeColor(int value)
```

Zwraca lub ustawia kolor określony w schemacie kolorów. Odczyt/zapis [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public abstract byte getR()
```

Zwraca lub ustawia komponentę czerwieni koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis byte.

**Zwraca:**
byte
### setR(byte value) {#setR-byte-}
```
public abstract void setR(byte value)
```

Zwraca lub ustawia komponentę czerwieni koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public abstract byte getG()
```

Zwraca lub ustawia komponentę zieleni koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis byte.

**Zwraca:**
byte
### setG(byte value) {#setG-byte-}
```
public abstract void setG(byte value)
```

Zwraca lub ustawia komponentę zieleni koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public abstract byte getB()
```

Zwraca lub ustawia komponentę niebieskiego koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis byte.

**Zwraca:**
byte
### setB(byte value) {#setB-byte-}
```
public abstract void setB(byte value)
```

Zwraca lub ustawia komponentę niebieskiego koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis byte.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public abstract float getFloatR()
```

Zwraca lub ustawia komponentę czerwieni koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setFloatR(float value) {#setFloatR-float-}
```
public abstract void setFloatR(float value)
```

Zwraca lub ustawia komponentę czerwieni koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public abstract float getFloatG()
```

Zwraca lub ustawia komponentę zieleni koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setFloatG(float value) {#setFloatG-float-}
```
public abstract void setFloatG(float value)
```

Zwraca lub ustawia komponentę zieleni koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public abstract float getFloatB()
```

Zwraca lub ustawia komponentę niebieskiego koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setFloatB(float value) {#setFloatB-float-}
```
public abstract void setFloatB(float value)
```

Zwraca lub ustawia komponentę niebieskiego koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public abstract float getHue()
```

Zwraca lub ustawia komponentę odcienia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setHue(float value) {#setHue-float-}
```
public abstract void setHue(float value)
```

Zwraca lub ustawia komponentę odcienia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public abstract float getSaturation()
```

Zwraca lub ustawia komponentę nasycenia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setSaturation(float value) {#setSaturation-float-}
```
public abstract void setSaturation(float value)
```

Zwraca lub ustawia komponentę nasycenia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public abstract float getLuminance()
```

Zwraca lub ustawia komponentę luminancji koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Zwraca:**
float
### setLuminance(float value) {#setLuminance-float-}
```
public abstract void setLuminance(float value)
```

Zwraca lub ustawia komponentę luminancji koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public abstract IColorOperationCollection getColorTransform()
```

Zwraca kolekcję transformacji koloru zastosowanych do koloru. Tylko do odczytu [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Zwraca:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)
### toString(int format) {#toString-int-}
```
public abstract String toString(int format)
```

Zwraca String, który reprezentuje aktualny format koloru.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| format | int | Typ formatu ciągu znaków koloru. |

**Zwraca:**
java.lang.String - Ciąg znaków, który reprezentuje aktualny format koloru.
### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public abstract void copyFrom(IColorFormat color)
```

Kopiuj format koloru z „color”.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) | Kolor [IColorFormat](../../com.aspose.slides/icolorformat) |