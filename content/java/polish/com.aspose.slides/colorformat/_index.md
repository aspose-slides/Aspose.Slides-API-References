---
title: ColorFormat
second_title: Aspose.Slides dla Java - Dokumentacja API
description: Reprezentuje kolor używany w prezentacji.
type: docs
url: /pl/com.aspose.slides/colorformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IColorFormat](../../com.aspose.slides/icolorformat)
```
public final class ColorFormat extends PVIObject implements IColorFormat
```

Reprezentuje kolor używany w prezentacji.
## Metody

| Metoda | Opis |
| --- | --- |
| [getColorType()](#getColorType--) | Zwraca lub ustawia metodę definiowania koloru. |
| [setColorType(int value)](#setColorType-int-) | Zwraca lub ustawia metodę definiowania koloru. |
| [getColor()](#getColor--) | Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). |
| [setColor(Color value)](#setColor-java.awt.Color-) | Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). |
| [getPresetColor()](#getPresetColor--) | Zwraca lub ustawia preset koloru. |
| [setPresetColor(int value)](#setPresetColor-int-) | Zwraca lub ustawia preset koloru. |
| [getSystemColor()](#getSystemColor--) | Zwraca lub ustawia kolor określony w tabeli kolorów systemu. |
| [setSystemColor(int value)](#setSystemColor-int-) | Zwraca lub ustawia kolor określony w tabeli kolorów systemu. |
| [getSchemeColor()](#getSchemeColor--) | Zwraca lub ustawia kolor określony w schemacie kolorów. |
| [setSchemeColor(int value)](#setSchemeColor-int-) | Zwraca lub ustawia kolor określony w schemacie kolorów. |
| [getR()](#getR--) | Zwraca lub ustawia składową czerwoną koloru. |
| [setR(byte value)](#setR-byte-) | Zwraca lub ustawia składową czerwoną koloru. |
| [getG()](#getG--) | Zwraca lub ustawia składową zieloną koloru. |
| [setG(byte value)](#setG-byte-) | Zwraca lub ustawia składową zieloną koloru. |
| [getB()](#getB--) | Zwraca lub ustawia składową niebieską koloru. |
| [setB(byte value)](#setB-byte-) | Zwraca lub ustawia składową niebieską koloru. |
| [getFloatR()](#getFloatR--) | Zwraca lub ustawia składową czerwoną koloru. |
| [setFloatR(float value)](#setFloatR-float-) | Zwraca lub ustawia składową czerwoną koloru. |
| [getFloatG()](#getFloatG--) | Zwraca lub ustawia składową zieloną koloru. |
| [setFloatG(float value)](#setFloatG-float-) | Zwraca lub ustawia składową zieloną koloru. |
| [getFloatB()](#getFloatB--) | Zwraca lub ustawia składową niebieską koloru. |
| [setFloatB(float value)](#setFloatB-float-) | Zwraca lub ustawia składową niebieską koloru. |
| [getHue()](#getHue--) | Zwraca lub ustawia składową odcienia koloru w reprezentacji HSL. |
| [setHue(float value)](#setHue-float-) | Zwraca lub ustawia składową odcienia koloru w reprezentacji HSL. |
| [getSaturation()](#getSaturation--) | Zwraca lub ustawia składową nasycenia koloru w reprezentacji HSL. |
| [setSaturation(float value)](#setSaturation-float-) | Zwraca lub ustawia składową nasycenia koloru w reprezentacji HSL. |
| [getLuminance()](#getLuminance--) | Zwraca lub ustawia składową luminancji koloru w reprezentacji HSL. |
| [setLuminance(float value)](#setLuminance-float-) | Zwraca lub ustawia składową luminancji koloru w reprezentacji HSL. |
| [getColorTransform()](#getColorTransform--) | Zwraca kolekcję transformacji koloru zastosowanych do koloru. |
| [toString(int format)](#toString-int-) | Zwraca ciąg znaków reprezentujący bieżący format koloru. |
| [copyFrom(IColorFormat color)](#copyFrom-com.aspose.slides.IColorFormat-) | Kopiuje format koloru z „color”. |
| [equals(Object obj)](#equals-java.lang.Object-) | Sprawdza równość z określonym obiektem. |
| [hashCode()](#hashCode--) | Zwraca kod hash. |
| [getVersion()](#getVersion--) |  |
| [getParent_ISlideComponent()](#getParent-ISlideComponent--) |  |
| [getParent_IPresentationComponent()](#getParent-IPresentationComponent--) |  |

### getColorType() {#getColorType--}
```
public final int getColorType()
```

Zwraca lub ustawia metodę definiowania koloru. Odczyt/zapis [ColorType](../../com.aspose.slides/colortype).

**Zwraca:**
int

### setColorType(int value) {#setColorType-int-}
```
public final void setColorType(int value)
```

Zwraca lub ustawia metodę definiowania koloru. Odczyt/zapis [ColorType](../../com.aspose.slides/colortype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getColor() {#getColor--}
```
public final Color getColor()
```

Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). Ustawia kolory RGB i usuwa wszystkie transformacje koloru. Odczyt/zapis java.awt.Color.

**Zwraca:**
java.awt.Color

### setColor(Color value) {#setColor-java.awt.Color-}
```
public final void setColor(Color value)
```

Zwraca wynikowy kolor (z zastosowanymi wszystkimi transformacjami koloru). Ustawia kolory RGB i usuwa wszystkie transformacje koloru. Odczyt/zapis java.awt.Color.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.Color |  |

### getPresetColor() {#getPresetColor--}
```
public final int getPresetColor()
```

Zwraca lub ustawia preset koloru. Odczyt/zapis [PresetColor](../../com.aspose.slides/presetcolor).

**Zwraca:**
int

### setPresetColor(int value) {#setPresetColor-int-}
```
public final void setPresetColor(int value)
```

Zwraca lub ustawia preset koloru. Odczyt/zapis [PresetColor](../../com.aspose.slides/presetcolor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSystemColor() {#getSystemColor--}
```
public final int getSystemColor()
```

Zwraca lub ustawia kolor określony w tabeli kolorów systemu. Odczyt/zapis [SystemColor](../../com.aspose.slides/systemcolor).

**Zwraca:**
int

### setSystemColor(int value) {#setSystemColor-int-}
```
public final void setSystemColor(int value)
```

Zwraca lub ustawia kolor określony w tabeli kolorów systemu. Odczyt/zapis [SystemColor](../../com.aspose.slides/systemcolor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSchemeColor() {#getSchemeColor--}
```
public final int getSchemeColor()
```

Zwraca lub ustawia kolor określony w schemacie kolorów. Odczyt/zapis [SchemeColor](../../com.aspose.slides/schemecolor).

**Zwraca:**
int

### setSchemeColor(int value) {#setSchemeColor-int-}
```
public final void setSchemeColor(int value)
```

Zwraca lub ustawia kolor określony w schemacie kolorów. Odczyt/zapis [SchemeColor](../../com.aspose.slides/schemecolor).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getR() {#getR--}
```
public final byte getR()
```

Zwraca lub ustawia składową czerwoną koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  byte .

**Zwraca:**
byte

### setR(byte value) {#setR-byte-}
```
public final void setR(byte value)
```

Zwraca lub ustawia składową czerwoną koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  byte .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getG() {#getG--}
```
public final byte getG()
```

Zwraca lub ustawia składową zieloną koloru. Wszystkie transformacje koloru są ignorowane.

**Zwraca:**
byte

### setG(byte value) {#setG-byte-}
```
public final void setG(byte value)
```

Zwraca lub ustawia składową zieloną koloru. Wszystkie transformacje koloru są ignorowane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getB() {#getB--}
```
public final byte getB()
```

Zwraca lub ustawia składową niebieską koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  byte .

**Zwraca:**
byte

### setB(byte value) {#setB-byte-}
```
public final void setB(byte value)
```

Zwraca lub ustawia składową niebieską koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  byte .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getFloatR() {#getFloatR--}
```
public final float getFloatR()
```

Zwraca lub ustawia składową czerwoną koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Zwraca:**
float

### setFloatR(float value) {#setFloatR-float-}
```
public final void setFloatR(float value)
```

Zwraca lub ustawia składową czerwoną koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFloatG() {#getFloatG--}
```
public final float getFloatG()
```

Zwraca lub ustawia składową zieloną koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Zwraca:**
float

### setFloatG(float value) {#setFloatG-float-}
```
public final void setFloatG(float value)
```

Zwraca lub ustawia składową zieloną koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getFloatB() {#getFloatB--}
```
public final float getFloatB()
```

Zwraca lub ustawia składową niebieską koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Zwraca:**
float

### setFloatB(float value) {#setFloatB-float-}
```
public final void setFloatB(float value)
```

Zwraca lub ustawia składową niebieską koloru. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getHue() {#getHue--}
```
public final float getHue()
```

Zwraca lub ustawia składową odcienia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Zwraca:**
float

### setHue(float value) {#setHue-float-}
```
public final void setHue(float value)
```

Zwraca lub ustawia składową odcienia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getSaturation() {#getSaturation--}
```
public final float getSaturation()
```

Zwraca lub ustawia składową nasycenia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Zwraca:**
float

### setSaturation(float value) {#setSaturation-float-}
```
public final void setSaturation(float value)
```

Zwraca lub ustawia składową nasycenia koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getLuminance() {#getLuminance--}
```
public final float getLuminance()
```

Zwraca lub ustawia składową luminancji koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Zwraca:**
float

### setLuminance(float value) {#setLuminance-float-}
```
public final void setLuminance(float value)
```

Zwraca lub ustawia składową luminancji koloru w reprezentacji HSL. Wszystkie transformacje koloru są ignorowane. Odczyt/zapis  float .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getColorTransform() {#getColorTransform--}
```
public final IColorOperationCollection getColorTransform()
```

Zwraca kolekcję transformacji koloru zastosowanych do koloru. Tylko do odczytu [IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection).

**Zwraca:**
[IColorOperationCollection](../../com.aspose.slides/icoloroperationcollection)

### toString(int format) {#toString-int-}
```
public final String toString(int format)
```

Zwraca ciąg znaków, który reprezentuje bieżący format koloru.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| format | int | Typ formatu ciągu kolorów. |

**Zwraca:**
java.lang.String - Ciąg znaków, który reprezentuje bieżący format koloru.

### copyFrom(IColorFormat color) {#copyFrom-com.aspose.slides.IColorFormat-}
```
public final void copyFrom(IColorFormat color)
```

Kopiuj format koloru z „color”.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| color | [IColorFormat](../../com.aspose.slides/icolorformat) |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Sprawdza równość z określonym obiektem.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| obj | java.lang.Object | Obiekt. |

**Zwraca:**
boolean - Prawda, jeśli obiekty są równe, w przeciwnym razie fałsz.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Zwraca kod hash.

**Zwraca:**
int - Kod hash.

### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long

### getParent_ISlideComponent() {#getParent-ISlideComponent--}
```
public final ISlideComponent getParent_ISlideComponent()
```

**Zwraca:**
[ISlideComponent](../../com.aspose.slides/islidecomponent)

### getParent_IPresentationComponent() {#getParent-IPresentationComponent--}
```
public final IPresentationComponent getParent_IPresentationComponent()
```

Zwraca nadrzędny IPresentationComponent. Tylko do odczytu [IPresentationComponent](../../com.aspose.slides/ipresentationcomponent).

**Zwraca:**
[IPresentationComponent](../../com.aspose.slides/ipresentationcomponent)