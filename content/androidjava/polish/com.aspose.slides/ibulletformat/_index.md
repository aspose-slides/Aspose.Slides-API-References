---
title: IBulletFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Reprezentuje właściwości formatowania punktora akapitu.
type: docs
url: /pl/com.aspose.slides/ibulletformat/
---```
public interface IBulletFormat
```

Reprezentuje właściwości formatowania punktora akapitu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getType()](#getType--) | Zwraca lub ustawia typ punktora akapitu bez dziedziczenia. |
| [setType(byte value)](#setType-byte-) | Zwraca lub ustawia typ punktora akapitu bez dziedziczenia. |
| [getChar()](#getChar--) | Zwraca lub ustawia znak punktora akapitu bez dziedziczenia. |
| [setChar(char value)](#setChar-char-) | Zwraca lub ustawia znak punktora akapitu bez dziedziczenia. |
| [getFont()](#getFont--) | Zwraca lub ustawia czcionkę punktora akapitu bez dziedziczenia. |
| [setFont(IFontData value)](#setFont-com.aspose.slides.IFontData-) | Zwraca lub ustawia czcionkę punktora akapitu bez dziedziczenia. |
| [getHeight()](#getHeight--) | Zwraca lub ustawia wysokość punktora akapitu bez dziedziczenia. |
| [setHeight(float value)](#setHeight-float-) | Zwraca lub ustawia wysokość punktora akapitu bez dziedziczenia. |
| [getColor()](#getColor--) | Zwraca format koloru punktora akapitu bez dziedziczenia. |
| [getPicture()](#getPicture--) | Zwraca obraz używany jako punktor w akapicie bez dziedziczenia. |
| [getNumberedBulletStartWith()](#getNumberedBulletStartWith--) | Zwraca lub ustawia pierwszą liczbę używaną dla grupy ponumerowanych punktorów bez dziedziczenia. |
| [setNumberedBulletStartWith(short value)](#setNumberedBulletStartWith-short-) | Zwraca lub ustawia pierwszą liczbę używaną dla grupy ponumerowanych punktorów bez dziedziczenia. |
| [getNumberedBulletStyle()](#getNumberedBulletStyle--) | Zwraca lub ustawia styl ponumerowanego punktora bez dziedziczenia. |
| [setNumberedBulletStyle(byte value)](#setNumberedBulletStyle-byte-) | Zwraca lub ustawia styl ponumerowanego punktora bez dziedziczenia. |
| [isBulletHardColor()](#isBulletHardColor--) | Określa, czy punktor ma własny kolor, czy dziedziczy go z pierwszej części w akapicie. |
| [setBulletHardColor(byte value)](#setBulletHardColor-byte-) | Określa, czy punktor ma własny kolor, czy dziedziczy go z pierwszej części w akapicie. |
| [isBulletHardFont()](#isBulletHardFont--) | Określa, czy punktor ma własną czcionkę, czy dziedziczy ją z pierwszej części w akapicie. |
| [setBulletHardFont(byte value)](#setBulletHardFont-byte-) | Określa, czy punktor ma własną czcionkę, czy dziedziczy ją z pierwszej części w akapicie. |
| [applyDefaultParagraphIndentsShifts()](#applyDefaultParagraphIndentsShifts--) | Ustawia domyślne niezerowe przesunięcia dla efektywnego wcięcia akapitu i lewego marginesu, gdy punkty są włączone (tak jak robi to PowerPoint po włączeniu punktów/ numeracji w akapicie). |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania punktora z zastosowaną dziedzicznością. |

### getType() {#getType--}
```
public abstract byte getType()
```

Zwraca lub ustawia typ punktora akapitu bez dziedziczenia. Odczyt/zapis [BulletType](../../com.aspose.slides/bullettype).

**Zwraca:**
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Zwraca lub ustawia typ punktora akapitu bez dziedziczenia. Odczyt/zapis [BulletType](../../com.aspose.slides/bullettype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getChar() {#getChar--}
```
public abstract char getChar()
```

Zwraca lub ustawia znak punktora akapitu bez dziedziczenia. Odczyt/zapis char.

**Zwraca:**
char

### setChar(char value) {#setChar-char-}
```
public abstract void setChar(char value)
```

Zwraca lub ustawia znak punktora akapitu bez dziedziczenia. Odczyt/zapis char.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char |  |

### getFont() {#getFont--}
```
public abstract IFontData getFont()
```

Zwraca lub ustawia czcionkę punktora akapitu bez dziedziczenia. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Zwraca:**
[IFontData](../../com.aspose.slides/ifontdata)

### setFont(IFontData value) {#setFont-com.aspose.slides.IFontData-}
```
public abstract void setFont(IFontData value)
```

Zwraca lub ustawia czcionkę punktora akapitu bez dziedziczenia. Odczyt/zapis [IFontData](../../com.aspose.slides/ifontdata).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | [IFontData](../../com.aspose.slides/ifontdata) |  |

### getHeight() {#getHeight--}
```
public abstract float getHeight()
```

Zwraca lub ustawia wysokość punktora akapitu bez dziedziczenia. Wartość Float.NaN określa, że punktor dziedziczy wysokość z pierwszej części w akapicie. Odczyt/zapis float.

**Zwraca:**
float

### setHeight(float value) {#setHeight-float-}
```
public abstract void setHeight(float value)
```

Zwraca lub ustawia wysokość punktora akapitu bez dziedziczenia. Wartość Float.NaN określa, że punktor dziedziczy wysokość z pierwszej części w akapicie. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```

Zwraca format koloru punktora akapitu bez dziedziczenia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getPicture() {#getPicture--}
```
public abstract ISlidesPicture getPicture()
```

Zwraca obraz używany jako punktor w akapicie bez dziedziczenia. Tylko do odczytu [ISlidesPicture](../../com.aspose.slides/islidespicture).

**Zwraca:**
[ISlidesPicture](../../com.aspose.slides/islidespicture)

### getNumberedBulletStartWith() {#getNumberedBulletStartWith--}
```
public abstract short getNumberedBulletStartWith()
```

Zwraca lub ustawia pierwszą liczbę używaną dla grupy ponumerowanych punktorów bez dziedziczenia. Odczyt/zapis short.

**Zwraca:**
short

### setNumberedBulletStartWith(short value) {#setNumberedBulletStartWith-short-}
```
public abstract void setNumberedBulletStartWith(short value)
```

Zwraca lub ustawia pierwszą liczbę używaną dla grupy ponumerowanych punktorów bez dziedziczenia. Odczyt/zapis short.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | short |  |

### getNumberedBulletStyle() {#getNumberedBulletStyle--}
```
public abstract byte getNumberedBulletStyle()
```

Zwraca lub ustawia styl ponumerowanego punktora bez dziedziczenia. Odczyt/zapis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Zwraca:**
byte

### setNumberedBulletStyle(byte value) {#setNumberedBulletStyle-byte-}
```
public abstract void setNumberedBulletStyle(byte value)
```

Zwraca lub ustawia styl ponumerowanego punktora bez dziedziczenia. Odczyt/zapis [NumberedBulletStyle](../../com.aspose.slides/numberedbulletstyle)(\#getNumberedBulletStyle.getNumberedBulletStyle/\#setNumberedBulletStyle(byte).setNumberedBulletStyle(byte)).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### isBulletHardColor() {#isBulletHardColor--}
```
public abstract byte isBulletHardColor()
```

Określa, czy punktor ma własny kolor, czy dziedziczy go z pierwszej części w akapicie. **NullableBool#True** jeśli punktor ma własny kolor i **NullableBool#False** jeśli punktor dziedziczy kolor z pierwszej części w akapicie. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setBulletHardColor(byte value) {#setBulletHardColor-byte-}
```
public abstract void setBulletHardColor(byte value)
```

Określa, czy punktor ma własny kolor, czy dziedziczy go z pierwszej części w akapicie. **NullableBool#True** jeśli punktor ma własny kolor i **NullableBool#False** jeśli punktor dziedziczy kolor z pierwszej części w akapicie. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### isBulletHardFont() {#isBulletHardFont--}
```
public abstract byte isBulletHardFont()
```

Określa, czy punktor ma własną czcionkę, czy dziedziczy ją z pierwszej części w akapicie. **NullableBool#True** jeśli punktor ma własną czcionkę i **NullableBool#False** jeśli punktor dziedziczy czcionkę z pierwszej części w akapicie. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Zwraca:**
byte

### setBulletHardFont(byte value) {#setBulletHardFont-byte-}
```
public abstract void setBulletHardFont(byte value)
```

Określa, czy punktor ma własną czcionkę, czy dziedziczy ją z pierwszej części w akapicie. **NullableBool#True** jeśli punktor ma własną czcionkę i **NullableBool#False** jeśli punktor dziedziczy czcionkę z pierwszej części w akapicie. Odczyt/zapis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### applyDefaultParagraphIndentsShifts() {#applyDefaultParagraphIndentsShifts--}
```
public abstract void applyDefaultParagraphIndentsShifts()
```

Ustawia domyślne niezerowe przesunięcia dla efektywnego wcięcia akapitu i lewego marginesu, gdy punkty są włączone (tak jak robi to PowerPoint po włączeniu punktów/ numeracji w akapicie). Jeśli punkty są wyłączone, to po prostu resetuje wcięcie akapitu i lewy margines (tak jak robi to PowerPoint po wyłączeniu punktów/ numeracji w akapicie). Przesunięcia wcięć są stosowane względem bieżącego kontekstu punktora – IBulletFormat.Type, .NumberedBulletStyle i FontHeight pierwszej części. Niezerowe przesunięcia wcięć są stosowane do efektywnego wcięcia i lewego marginesu bieżącego akapitu (sprawiając, że wartości wynikowe są wartościami lokalnymi).

### getEffective() {#getEffective--}
```
public abstract IBulletFormatEffectiveData getEffective()
```

Zwraca skuteczne dane formatowania punktora z zastosowaną dziedzicznością.

--------------------

> ```
> This example demonstrates getting some effective bullet format properties.
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