---
title: IParagraphFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Ta klasa zawiera właściwości formatowania akapitu.
type: docs
url: /pl/com.aspose.slides/iparagraphformat/
---```
public interface IParagraphFormat
```

Ta klasa zawiera właściwości formatowania akapitu. W przeciwieństwie do [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata), wszystkie właściwości tej klasy są zapisywalne.

--------------------

Ta klasa jest używana do zwracania i manipulacji właściwościami formatowania akapitu zdefiniowanymi dla konkretnego akapitu. Oznacza to, że przy pobieraniu wartości nie jest stosowane dziedziczenie, więc w większości przypadków otrzymasz wartości oznaczające „niezdefiniowane”.

Aby uzyskać skuteczne wartości parametrów formatowania, w tym odziedziczone, należy użyć metody [getEffective](../../com.aspose.slides/iparagraphformat\#getEffective), która zwraca instancję [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).

## Metody

| Metoda | Opis |
| --- | --- |
| [getBullet()](#getBullet--) | Zwraca format wypunktowania akapitu. |
| [getDepth()](#getDepth--) | Zwraca lub ustawia głębokość akapitu. |
| [setDepth(short value)](#setDepth-short-) | Zwraca lub ustawia głębokość akapitu. |
| [getAlignment()](#getAlignment--) | Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. |
| [setAlignment(int value)](#setAlignment-int-) | Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. |
| [getSpaceWithin()](#getSpaceWithin--) | Zwraca lub ustawia ilość odstępu pomiędzy liniami bazowymi w akapicie. |
| [setSpaceWithin(float value)](#setSpaceWithin-float-) | Zwraca lub ustawia ilość odstępu pomiędzy liniami bazowymi w akapicie. |
| [getSpaceBefore()](#getSpaceBefore--) | Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. |
| [setSpaceBefore(float value)](#setSpaceBefore-float-) | Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. |
| [getSpaceAfter()](#getSpaceAfter--) | Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. |
| [setSpaceAfter(float value)](#setSpaceAfter-float-) | Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Określa, czy w akapicie używany jest podział linii wschodnioazjatycki. |
| [setEastAsianLineBreak(byte value)](#setEastAsianLineBreak-byte-) | Określa, czy w akapicie używany jest podział linii wschodnioazjatycki. |
| [getRightToLeft()](#getRightToLeft--) | Określa, czy w akapicie używany jest zapis od prawej do lewej. |
| [setRightToLeft(byte value)](#setRightToLeft-byte-) | Określa, czy w akapicie używany jest zapis od prawej do lewej. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Określa, czy w akapicie używany jest podział linii łacińskiej. |
| [setLatinLineBreak(byte value)](#setLatinLineBreak-byte-) | Określa, czy w akapicie używany jest podział linii łacińskiej. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Określa, czy w akapicie używana jest zawieszona interpunkcja. |
| [setHangingPunctuation(byte value)](#setHangingPunctuation-byte-) | Określa, czy w akapicie używana jest zawieszona interpunkcja. |
| [getMarginLeft()](#getMarginLeft--) | Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. |
| [setMarginLeft(float value)](#setMarginLeft-float-) | Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. |
| [getMarginRight()](#getMarginRight--) | Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. |
| [setMarginRight(float value)](#setMarginRight-float-) | Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. |
| [getIndent()](#getIndent--) | Zwraca lub ustawia wcięcie pierwszej linii/odwieszenia akapitu bez dziedziczenia. |
| [setIndent(float value)](#setIndent-float-) | Zwraca lub ustawia wcięcie pierwszej linii/odwieszenia akapitu bez dziedziczenia. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. |
| [setDefaultTabSize(float value)](#setDefaultTabSize-float-) | Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. |
| [getTabs()](#getTabs--) | Zwraca tabulacje akapitu. |
| [getFontAlignment()](#getFontAlignment--) | Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. |
| [setFontAlignment(int value)](#setFontAlignment-int-) | Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Zwraca domyślny format części akapitu. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania akapitu z zastosowanym dziedziczeniem. |

### getBullet() {#getBullet--}
```
public abstract IBulletFormat getBullet()
```

Zwraca format wypunktowania akapitu. Tylko do odczytu [IBulletFormat](../../com.aspose.slides/ibulletformat).

**Zwraca:**
[IBulletFormat](../../com.aspose.slides/ibulletformat)

### getDepth() {#getDepth--}
```
public abstract short getDepth()
```

Zwraca lub ustawia głębokość akapitu. Wartość 0 oznacza wartość niezdefiniowaną. Odczyt/zapis typu short.

**Zwraca:**
short

### setDepth(short value) {#setDepth-short-}
```
public abstract void setDepth(short value)
```

Zwraca lub ustawia głębokość akapitu. Wartość 0 oznacza wartość niezdefiniowaną. Odczyt/zapis typu short.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | short |  |

### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```

Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. Odczyt/zapis [TextAlignment](../../com.aspose.slides/textalignment).

**Zwraca:**
int

### setAlignment(int value) {#setAlignment-int-}
```
public abstract void setAlignment(int value)
```

Zwraca lub ustawia wyrównanie tekstu w akapicie bez dziedziczenia. Odczyt/zapis [TextAlignment](../../com.aspose.slides/textalignment).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```

Zwraca lub ustawia ilość odstępu pomiędzy liniami bazowymi w akapicie. Pozytywna wartość oznacza procent, ujemna – rozmiar w punktach. Nie stosuje się dziedziczenia. Odczyt/zapis float.

**Zwraca:**
float

### setSpaceWithin(float value) {#setSpaceWithin-float-}
```
public abstract void setSpaceWithin(float value)
```

Zwraca lub ustawia ilość odstępu pomiędzy liniami bazowymi w akapicie. Pozytywna wartość oznacza procent, ujemna – rozmiar w punktach. Nie stosuje się dziedziczenia. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```

Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Pozytywna wartość określa procent rozmiaru czcionki, który ma stanowić biały odstęp. Ujemna wartość określa rozmiar białego odstępu w punktach. Odczyt/zapis float.

**Zwraca:**
float

### setSpaceBefore(float value) {#setSpaceBefore-float-}
```
public abstract void setSpaceBefore(float value)
```

Zwraca lub ustawia ilość odstępu przed pierwszą linią w akapicie bez dziedziczenia. Pozytywna wartość określa procent rozmiaru czcionki, który ma stanowić biały odstęp. Ujemna wartość określa rozmiar białego odstępu w punktach. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```

Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Pozytywna wartość określa procent rozmiaru czcionki, który ma stanowić biały odstęp. Ujemna wartość określa rozmiar białego odstępu w punktach. Odczyt/zapis float.

**Zwraca:**
float

### setSpaceAfter(float value) {#setSpaceAfter-float-}
```
public abstract void setSpaceAfter(float value)
```

Zwraca lub ustawia ilość odstępu po ostatniej linii w akapicie bez dziedziczenia. Pozytywna wartość określa procent rozmiaru czcionki, który ma stanowić biały odstęp. Ujemna wartość określa rozmiar białego odstępu w punktach. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract byte getEastAsianLineBreak()
```

Określa, czy w akapicie używany jest podział linii wschodnioazjatycki. Nie stosuje się dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setEastAsianLineBreak(byte value) {#setEastAsianLineBreak-byte-}
```
public abstract void setEastAsianLineBreak(byte value)
```

Określa, czy w akapicie używany jest podział linii wschodnioazjatycki. Nie stosuje się dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getRightToLeft() {#getRightToLeft--}
```
public abstract byte getRightToLeft()
```

Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie stosuje się dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setRightToLeft(byte value) {#setRightToLeft-byte-}
```
public abstract void setRightToLeft(byte value)
```

Określa, czy w akapicie używany jest zapis od prawej do lewej. Nie stosuje się dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract byte getLatinLineBreak()
```

Określa, czy w akapicie używany jest podział linii łacińskiej. Nie stosuje się dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setLatinLineBreak(byte value) {#setLatinLineBreak-byte-}
```
public abstract void setLatinLineBreak(byte value)
```

Określa, czy w akapicie używany jest podział linii łacińskiej. Nie stosuje się dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract byte getHangingPunctuation()
```

Określa, czy w akapicie używana jest zawieszona interpunkcja. Nie stosuje się dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setHangingPunctuation(byte value) {#setHangingPunctuation-byte-}
```
public abstract void setHangingPunctuation(byte value)
```

Określa, czy w akapicie używana jest zawieszona interpunkcja. Nie stosuje się dziedziczenia. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```

Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. Odczyt/zapis float.

**Zwraca:**
float

### setMarginLeft(float value) {#setMarginLeft-float-}
```
public abstract void setMarginLeft(float value)
```

Zwraca lub ustawia lewy margines w akapicie bez dziedziczenia. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```

Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. Odczyt/zapis float.

**Zwraca:**
float

### setMarginRight(float value) {#setMarginRight-float-}
```
public abstract void setMarginRight(float value)
```

Zwraca lub ustawia prawy margines w akapicie bez dziedziczenia. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getIndent() {#getIndent--}
```
public abstract float getIndent()
```

Zwraca lub ustawia wcięcie pierwszej linii/odwieszenia akapitu bez dziedziczenia. Wcięcie odwieszone może być określone wartościami ujemnymi. Odczyt/zapis float.

**Zwraca:**
float

### setIndent(float value) {#setIndent-float-}
```
public abstract void setIndent(float value)
```

Zwraca lub ustawia wcięcie pierwszej linii/odwieszenia akapitu bez dziedziczenia. Wcięcie odwieszone może być określone wartościami ujemnymi. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```

Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. Odczyt/zapis float.

**Zwraca:**
float

### setDefaultTabSize(float value) {#setDefaultTabSize-float-}
```
public abstract void setDefaultTabSize(float value)
```

Zwraca lub ustawia domyślny rozmiar tabulacji bez dziedziczenia. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getTabs() {#getTabs--}
```
public abstract ITabCollection getTabs()
```

Zwraca tabulacje akapitu. Nie stosuje się dziedziczenia. Tylko do odczytu [ITabCollection](../../com.aspose.slides/itabcollection).

**Zwraca:**
[ITabCollection](../../com.aspose.slides/itabcollection)

### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```

Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. Odczyt/zapis [FontAlignment](../../com.aspose.slides/fontalignment).

**Zwraca:**
int

### setFontAlignment(int value) {#setFontAlignment-int-}
```
public abstract void setFontAlignment(int value)
```

Zwraca lub ustawia wyrównanie czcionki w akapicie bez dziedziczenia. Odczyt/zapis [FontAlignment](../../com.aspose.slides/fontalignment).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormat getDefaultPortionFormat()
```

Zwraca domyślny format części akapitu. Nie stosuje się dziedziczenia. Tylko do odczytu [IPortionFormat](../../com.aspose.slides/iportionformat).

**Zwraca:**
[IPortionFormat](../../com.aspose.slides/iportionformat)

### getEffective() {#getEffective--}
```
public abstract IParagraphFormatEffectiveData getEffective()
```

Pobiera skuteczne dane formatowania akapitu z zastosowanym dziedziczeniem.

**Zwraca:**
[IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata) - A [IParagraphFormatEffectiveData](../../com.aspose.slides/iparagraphformateffectivedata).