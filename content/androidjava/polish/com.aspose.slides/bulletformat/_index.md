---
title: BulletFormat
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Reprezentuje właściwości formatowania punktorów akapitu.
type: docs
url: /pl/com.aspose.slides/bulletformat/
---
**Dziedziczenie:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IBulletFormat](../../com.aspose.slides/ibulletformat)
```
public final class BulletFormat extends PVIObject implements IBulletFormat
```

Reprezentuje właściwości formatowania punktorów akapitu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Zwraca lub ustawia typ wypunktowania akapitu bez dziedziczenia. |
| [setType(byte value)](#setType-byte-) | Zwraca lub ustawia typ wypunktowania akapitu bez dziedziczenia. |
| [getChar()](#getChar--) | Zwraca lub ustawia znak wypunktowania akapitu bez dziedziczenia. |
| [setChar(char value)](#setChar-char-) | Zwraca lub ustawia znak wypunktowania akapitu bez dziedziczenia. |
| [getFont()](#getFont--) | Zwraca lub ustawia czcionkę wypunktowania akapitu bez dziedziczenia. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę wypunktowania akapitu bez dziedziczenia. |
| [getHeight()](#getHeight--) | Zwraca lub ustawia wysokość wypunktowania akapitu bez dziedziczenia. |
| [setHeight(float value)](#setHeight-float-) | Zwraca lub ustawia wysokość wypunktowania akapitu bez dziedziczenia. |
| [getColor()](#getColor--) | Zwraca format koloru wypunktowania akapitu bez dziedziczenia. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Zwraca lub ustawia pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Zwraca lub ustawia pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Zwraca lub ustawia styl numerowanego wypunktowania bez dziedziczenia. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Zwraca lub ustawia styl numerowanego wypunktowania bez dziedziczenia. |
| [isBulletHardColor()](#isBulletHardColor--) | Określa, czy wypunktowanie ma własny kolor lub dziedziczy go od pierwszej części w akapicie. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Określa, czy wypunktowanie ma własny kolor lub dziedziczy go od pierwszej części w akapicie. |
| [isBulletHardFont()](#isBulletHardFont--) | Określa, czy wypunktowanie ma własną czcionkę lub dziedziczy ją od pierwszej części w akapicie. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Określa, czy wypunktowanie ma własną czcionkę lub dziedziczy ją od pierwszej części w akapicie. |
| [getPicture()](#getPicture--) | Zwraca obraz używany jako wypunktowanie w akapicie bez dziedziczenia. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Ustawia domyślne niezerowe przesunięcia dla skutecznego wcięcia akapitu i lewej marginesu, gdy wypunktowanie jest włączone (jak robi PowerPoint po włączeniu wypunktowania/umerowania w akapicie). |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania wypunktowania z zastosowanym dziedziczeniem. |
| [getVersion()](#getVersion--) |  |

### getType() {#getType--}
```
public final byte getType()
```

Zwraca lub ustawia typ wypunktowania akapitu bez dziedziczenia. Odczyt/zapis [BulletType](../../com.aspose.slides/bullettype).

**Zwraca:**
byte

### setType(byte value) {#setType-byte-}
```
public final void setType(byte value)
```

Zwraca lub ustawia typ wypunktowania akapitu bez dziedziczenia. Odczyt/zapis [BulletType](../../com.aspose.slides/bullettype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public final char getChar()
```

Zwraca lub ustawia znak wypunktowania akapitu bez dziedziczenia. Odczyt/zapis  char .

**Zwraca:**
char

### setChar(char value) {#setChar-char-}
```
public final void setChar(char value)
```

Zwraca lub ustawia znak wypunktowania akapitu bez dziedziczenia. Odczyt/zapis  char .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public final IFontData getFont()
```

Zwraca lub ustawia czcionkę wypunktowania akapitu bez dziedziczenia. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public final void setFont(IFontData value)
```

Zwraca lub ustawia czcionkę wypunktowania akapitu bez dziedziczenia. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public final float getHeight()
```

Zwraca lub ustawia wysokość wypunktowania akapitu bez dziedziczenia. Wartość Float.NaN określa, że wypunktowanie dziedziczy wysokość od pierwszej części w akapicie. Odczyt/zapis  float .

--------------------

Ujemna wartość wysokości oznacza, że wysokość jest podana w punktach, a dodatnia wartość oznacza, że wysokość jest procentem otaczającego tekstu.

**Zwraca:**
float

### setHeight(float value) {#setHeight-float-}
```
public final void setHeight(float value)
```

Zwraca lub ustawia wysokość wypunktowania akapitu bez dziedziczenia. Wartość Float.NaN określa, że wypunktowanie dziedziczy wysokość od pierwszej części w akapicie. Odczyt/zapis  float .

--------------------

Ujemna wartość wysokości oznacza, że wysokość jest podana w punktach, a dodatnia wartość oznacza, że wysokość jest procentem otaczającego tekstu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Zwraca format koloru wypunktowania akapitu bez dziedziczenia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public final short getNumberedBulletStartWith()
```

Zwraca lub ustawia pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia. Odczyt/zapis  short .

**Zwraca:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public final void setNumberedBulletStartWith(short value)
```

Zwraca lub ustawia pierwszą liczbę używaną dla grupy numerowanych wypunktowań bez dziedziczenia. Odczyt/zapis  short .

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public final byte getNumberedBulletStyle()
```

Zwraca lub ustawia styl numerowanego wypunktowania bez dziedziczenia. Odczyt/zapis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Zwraca:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public final void setNumberedBulletStyle(byte value)
```

Zwraca lub ustawia styl numerowanego wypunktowania bez dziedziczenia. Odczyt/zapis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public final byte isBulletHardColor()
```

Określa, czy wypunktowanie ma własny kolor lub dziedziczy go od pierwszej części w akapicie. **NullableBool.True** jeśli wypunktowanie ma własny kolor i **NullableBool.False** jeśli wypunktowanie dziedziczy kolor od pierwszej części w akapicie. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public final void setBulletHardColor(byte value)
```

Określa, czy wypunktowanie ma własny kolor lub dziedziczy go od pierwszej części w akapicie. **NullableBool.True** jeśli wypunktowanie ma własny kolor i **NullableBool.False** jeśli wypunktowanie dziedziczy kolor od pierwszej części w akapicie. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public final byte isBulletHardFont()
```

Określa, czy wypunktowanie ma własną czcionkę lub dziedziczy ją od pierwszej części w akapicie. **NullableBool.True** jeśli wypunktowanie ma własną czcionkę i **NullableBool.False** jeśli wypunktowanie dziedziczy czcionkę od pierwszej części w akapicie. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public final void setBulletHardFont(byte value)
```

Określa, czy wypunktowanie ma własną czcionkę lub dziedziczy ją od pierwszej części w akapicie. **NullableBool.True** jeśli wypunktowanie ma własną czcionkę i **NullableBool.False** jeśli wypunktowanie dziedziczy czcionkę od pierwszej części w akapicie. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getPicture() {#getPicture--}
```
public final ISlidesPicture getPicture()
```

Zwraca obraz używany jako wypunktowanie w akapicie bez dziedziczenia. Tylko do odczytu [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Zwraca:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public final void applyDefaultParagraphIndentsShifts()
```

Ustawia domyślne niezerowe przesunięcia dla skutecznego wcięcia akapitu i lewej marginesu, gdy wypunktowanie jest włączone (tak jak PowerPoint robi po włączeniu wypunktowania/umerowania w akapicie). Jeśli wypunktowanie jest wyłączone, po prostu resetuje wcięcie akapitu i lewą margines (tak jak PowerPoint robi po wyłączeniu wypunktowania/umerowania w akapicie). Przesunięcia wcięć są stosowane w odniesieniu do bieżącego kontekstu wypunktowania - IBulletFormat.Type, .NumberedBulletStyle i FontHeight pierwszej części. Niezerowe przesunięcia wcięć są stosowane do skutecznego wcięcia i lewej marginesu bieżącego akapitu (sprawiając, że wartości wynikowe są wartościami lokalnymi).

### getEffective() {#getEffective--}
```
public final IBulletFormatEffectiveData getEffective()
```

Pobiera skuteczne dane formatowania wypunktowania z zastosowanym dziedziczeniem.

--------------------

> ```
> Ten przykład demonstruje pobieranie niektórych efektywnych właściwości formatu wypunktowania.
>  
>  Presentation pres = new Presentation("MyPresentation.pptx");
>  try {
>      IAutoShape shape = (IAutoShape)pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      IBulletFormatEffectiveData effectiveBulletFormat = shape.getTextFrame().getParagraphs().get_Item(0).getParagraphFormat().getBullet().getEffective();
>      System.out.println("Bullet type: " + effectiveBulletFormat.getType());
>      if (effectiveBulletFormat.getType() == BulletType.Numbered)
>      {
>          System.out.println("Numbered style: " + effectiveBulletFormat.getNumberedBulletStyle());
>          System.out.println("Starting number: " + effectiveBulletFormat.getNumberedBulletStartWith());
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Zwraca:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata) - A [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Wersja. Tylko do odczytu long.

**Zwraca:**
long