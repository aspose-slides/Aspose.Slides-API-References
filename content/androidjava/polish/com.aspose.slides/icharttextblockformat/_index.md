---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje właściwości formatowania dla elementów tekstowych wykresu.
type: docs
url: /pl/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Reprezentuje właściwości formatowania dla elementów tekstowych wykresu.
## Metody

| Method | Description |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Zwraca lub ustawia pionowy tekst zakotwienia w TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Zwraca lub ustawia pionowy tekst zakotwienia w TextFrame. |
| [getCenterText()](#getCenterText--) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w ramce w poziomie. |
| [setCenterText(byte value)](#setCenterText-byte-) | Jeśli NullableBool.True, tekst powinien być wyśrodkowany w ramce w poziomie. |
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
| [getAutofitType()](#getAutofitType--) | Zwraca lub ustawia tryb automatycznego dopasowania tekstu. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Zwraca lub ustawia tryb automatycznego dopasowania tekstu. |
| [getRotationAngle()](#getRotationAngle--) | Określa niestandardowy obrót stosowany do tekstu w obrębie pola ograniczającego. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Określa niestandardowy obrót stosowany do tekstu w obrębie pola ograniczającego. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Zwraca lub ustawia pionowy tekst zakotwienia w TextFrame. Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**Zwraca:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Zwraca lub ustawia pionowy tekst zakotwienia w TextFrame. Read/write [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Jeśli NullableBool.True, tekst powinien być wyśrodkowany w ramce w poziomie. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Jeśli NullableBool.True, tekst powinien być wyśrodkowany w ramce w poziomie. Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i niestandardowego kąta w właściwości RotationAngle. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Zwraca:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Określa orientację tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i niestandardowego kąta w właściwości RotationAngle. Read/write [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Zwraca lub ustawia lewy margines (punkty) w TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write double.

**Zwraca:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Zwraca lub ustawia lewy margines (punkty) w TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write double.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Zwraca lub ustawia prawy margines (punkty) w TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write double.

**Zwraca:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Zwraca lub ustawia prawy margines (punkty) w TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write double.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Zwraca lub ustawia górny margines (punkty) w TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write double.

**Zwraca:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Zwraca lub ustawia górny margines (punkty) w TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write double.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Zwraca lub ustawia dolny margines (punkty) w TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write double.

**Zwraca:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Zwraca lub ustawia dolny margines (punkty) w TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write double.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2007/2013). Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

Prawda, jeśli tekst jest zawijany przy marginesach TextFrame. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2007/2013). Read/write [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Zwraca lub ustawia tryb automatycznego dopasowania tekstu. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write [TextAutofitType](../../com.aspose.slides/textautofittype).

**Zwraca:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Zwraca lub ustawia tryb automatycznego dopasowania tekstu. Zmiana tej właściwości może mieć wpływ tylko na następujące części wykresu: DataLabel i DataLabelFormat (pełne wsparcie w PowerPoint 2013; w PowerPoint 2007 nie ma efektu przy renderowaniu). Read/write [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Określa niestandardowy obrót stosowany do tekstu w obrębie pola ograniczającego. Jeśli nie jest określony, używany jest obrót powiązanej figury. Jeśli jest określony, jest stosowany niezależnie od figury. To znaczy, figura może mieć obrót dodatkowy względem obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i predefiniowanego pionowego typu w właściwości TextVerticalType. Read/write float.

--------------------

> ```
> Rozważmy przypadek, w którym kształt ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. 
>  Dodatkowo ciało tekstu ma zastosowany obrót o -90 stopni przeciwnie do ruchu wskazówek zegara 
>  Wtedy wynikowy kształt będzie wyglądał na obrócony, ale tekst w nim będzie wyglądał tak, jakby nie był wcale obrócony.
> ```

**Zwraca:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Określa niestandardowy obrót stosowany do tekstu w obrębie pola ograniczającego. Jeśli nie jest określony, używany jest obrót powiązanej figury. Jeśli jest określony, jest stosowany niezależnie od figury. To znaczy, figura może mieć obrót dodatkowy względem obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowaniem tej właściwości i predefiniowanego pionowego typu w właściwości TextVerticalType. Read/write float.

--------------------

> ```
> Rozważmy przypadek, w którym kształt ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. 
>  Dodatkowo ciało tekstu ma zastosowany obrót o -90 stopni 
>  przeciwnie do ruchu wskazówek zegara. Następnie wynikowy kształt będzie wyglądał jakby
>  został obrócony, ale tekst w nim będzie wydawał się, jakby nie został w ogóle obrócony.
```

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |