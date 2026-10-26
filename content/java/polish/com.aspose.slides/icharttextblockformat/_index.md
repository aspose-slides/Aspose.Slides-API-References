---
title: IChartTextBlockFormat
second_title: Aspose.Slides dla Java API Referencja
description: Reprezentuje właściwości formatowania elementów tekstowych wykresu.
type: docs
url: /pl/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Reprezentuje właściwości formatowania elementów tekstowych wykresu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Zwraca lub ustawia pionowe zakotwienie tekstu w TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Zwraca lub ustawia pionowe zakotwienie tekstu w TextFrame. |
| [getCenterText()](#getCenterText--) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w polu. |
| [setCenterText(byte value)](#setCenterText-byte-) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w polu. |
| [getTextVerticalType()](#getTextVerticalType--) | Określa orientację tekstu. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Określa orientację tekstu. |
| [getMarginLeft()](#getMarginLeft--) | Zwraca lub ustawia lewy margines (punkty) w TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Zwraca lub ustawia lewy margines (punkty) w TextFrame. |
| [getMarginRight()](#getMarginRight--) | Zwraca lub ustawia prawy margines (punkty) w TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Zwraca lub ustawia prawy margines (punkty) w TextFrame. |
| [getMarginTop()](#getMarginTop--) | Zwraca lub ustawia górny margines (punkty) w TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Zwraca lub ustawia górny margines (punkty) w TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Zwraca lub ustawia dolny margines (punkty) w TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Zwraca lub ustawia dolny margines (punkty) w TextFrame. |
| [getWrapText()](#getWrapText--) | Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. |
| [getAutofitType()](#getAutofitType--) | Zwraca lub ustawia tryb automatycznego dopasowywania tekstu. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Zwraca lub ustawia tryb automatycznego dopasowywania tekstu. |
| [getRotationAngle()](#getRotationAngle--) | Określa niestandardowy obrót, który jest stosowany do tekstu wewnątrz ramki ograniczającej. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Określa niestandardowy obrót, który jest stosowany do tekstu wewnątrz ramki ograniczającej. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Zwraca lub ustawia pionowe zakotwienie tekstu w TextFrame. Odczyt/zapis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Zwraca:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Zwraca lub ustawia pionowe zakotwienie tekstu w TextFrame. Odczyt/zapis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w polu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Jeśli NullableBool.True, tekst powinien być wyśrodkowany w poziomie w polu. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i niestandardowego kąta w właściwości RotationAngle. Odczyt/zapis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Zwraca:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i niestandardowego kąta w właściwości RotationAngle. Odczyt/zapis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Zwraca lub ustawia lewy margines (punkty) w TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis double.

**Zwraca:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Zwraca lub ustawia lewy margines (punkty) w TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Zwraca lub ustawia prawy margines (punkty) w TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis double.

**Zwraca:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Zwraca lub ustawia prawy margines (punkty) w TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Zwraca lub ustawia górny margines (punkty) w TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis double.

**Zwraca:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Zwraca lub ustawia górny margines (punkty) w TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Zwraca lub ustawia dolny margines (punkty) w TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis double.

**Zwraca:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Zwraca lub ustawia dolny margines (punkty) w TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2007/2013). Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2007/2013). Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Zwraca lub ustawia tryb automatycznego dopasowywania tekstu. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Zwraca:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Zwraca lub ustawia tryb automatycznego dopasowywania tekstu. Zmiana tej właściwości może wywołać określony wpływ tylko dla następujących elementów wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Odczyt/zapis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki ograniczającej. Jeśli nie jest określony, używany jest obrót powiązanej figury. Jeśli jest określony, jest on stosowany niezależnie od figury. Oznacza to, że figura może mieć zastosowany obrót dodatkowo do obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i predefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt/zapis float.

--------------------

> ```
> Rozważmy przypadek, w którym figura ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. 
>  Dodatkowo sam tekst ma zastosowany obrót o -90 stopni 
>  przeciwnie do ruchu wskazówek zegara. Wtedy wynikowa figura wydawałaby się
>  być obrócona, ale tekst wewnątrz niej wyglądałby tak, jakby wcale nie został obrócony.
> ```


**Zwraca:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki ograniczającej. Jeśli nie jest określony, używany jest obrót powiązanej figury. Jeśli jest określony, jest on stosowany niezależnie od figury. Oznacza to, że figura może mieć zastosowany obrót dodatkowo do obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej właściwości i predefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt/zapis float.

--------------------

> ```
> Rozważmy przypadek, w którym figura ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. 
>  Dodatkowo sam tekst ma zastosowany obrót o -90 stopni 
>  przeciwnie do ruchu wskazówek zegara. Wtedy wynikowa figura wydawałaby się
>  być obrócona, ale tekst wewnątrz niej wyglądałby tak, jakby wcale nie został obrócony.
> ```

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |