---
title: IParagraphFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Niezmienny obiekt zawierający skuteczne właściwości formatowania akapitu.
type: docs
url: /pl/com.aspose.slides/iparagraphformateffectivedata/
---```
public interface IParagraphFormatEffectiveData
```

Niezmienny obiekt zawierający skuteczne właściwości formatowania akapitu.

--------------------

Ten interfejs jest używany razem z interfejsem [IParagraphFormat](../../com.aspose.slides/iparagraphformat) w celu zwrócenia efektywnych wartości formatowania z zastosowaniem dziedziczenia.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBullet()](#getBullet--) | Zwraca format wypunktowania akapitu. |
| [getDepth()](#getDepth--) | Zwraca głębokość akapitu. |
| [getAlignment()](#getAlignment--) | Zwraca wyrównanie tekstu w akapicie. |
| [getSpaceWithin()](#getSpaceWithin--) | Zwraca ilość odstępu między liniami bazowymi w akapicie. |
| [getSpaceBefore()](#getSpaceBefore--) | Zwraca ilość odstępu przed pierwszą linią w akapicie. |
| [getSpaceAfter()](#getSpaceAfter--) | Zwraca ilość odstępu po ostatniej linii w akapicie. |
| [getEastAsianLineBreak()](#getEastAsianLineBreak--) | Określa, czy w akapicie używany jest podział linii Azji Wschodniej. |
| [getRightToLeft()](#getRightToLeft--) | Określa, czy w akapicie używany jest zapis od prawej do lewej. |
| [getLatinLineBreak()](#getLatinLineBreak--) | Określa, czy w akapicie używany jest podział linii łacińskiej. |
| [getHangingPunctuation()](#getHangingPunctuation--) | Określa, czy w akapicie używana jest wieszająca interpunkcja. |
| [getMarginLeft()](#getMarginLeft--) | Zwraca lewy margines w akapicie. |
| [getMarginRight()](#getMarginRight--) | Zwraca prawy margines w akapicie. |
| [getIndent()](#getIndent--) | Zwraca wcięcie pierwszej linii/odwieszenie akapitu. |
| [getDefaultTabSize()](#getDefaultTabSize--) | Zwraca domyślny rozmiar tabulacji. |
| [getTabs()](#getTabs--) | Zwraca tabulacje akapitu. |
| [getFontAlignment()](#getFontAlignment--) | Zwraca wyrównanie czcionki w akapicie. |
| [getDefaultPortionFormat()](#getDefaultPortionFormat--) | Zwraca domyślny format fragmentu w akapicie. |
### getBullet() {#getBullet--}
```
public abstract IBulletFormatEffectiveData getBullet()
```


Zwraca format wypunktowania akapitu. Tylko do odczytu [IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata).

**Zwraca:**
[IBulletFormatEffectiveData](../../com.aspose.slides/ibulletformateffectivedata)
### getDepth() {#getDepth--}
```
public abstract short getDepth()
```


Zwraca głębokość akapitu. Tylko do odczytu short.

**Zwraca:**
short
### getAlignment() {#getAlignment--}
```
public abstract int getAlignment()
```


Zwraca wyrównanie tekstu w akapicie. Tylko do odczytu [TextAlignment](../../com.aspose.slides/textalignment).

**Zwraca:**
int
### getSpaceWithin() {#getSpaceWithin--}
```
public abstract float getSpaceWithin()
```


Zwraca ilość odstępu między liniami bazowymi w akapicie. Tylko do odczytu float.

**Zwraca:**
float
### getSpaceBefore() {#getSpaceBefore--}
```
public abstract float getSpaceBefore()
```


Zwraca ilość odstępu przed pierwszą linią w akapicie. Tylko do odczytu float.

**Zwraca:**
float
### getSpaceAfter() {#getSpaceAfter--}
```
public abstract float getSpaceAfter()
```


Zwraca ilość odstępu po ostatniej linii w akapicie. Tylko do odczytu float.

**Zwraca:**
float
### getEastAsianLineBreak() {#getEastAsianLineBreak--}
```
public abstract boolean getEastAsianLineBreak()
```


Określa, czy w akapicie używany jest podział linii Azji Wschodniej. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getRightToLeft() {#getRightToLeft--}
```
public abstract boolean getRightToLeft()
```


Określa, czy w akapicie używany jest zapis od prawej do lewej. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getLatinLineBreak() {#getLatinLineBreak--}
```
public abstract boolean getLatinLineBreak()
```


Określa, czy w akapicie używany jest podział linii łacińskiej. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getHangingPunctuation() {#getHangingPunctuation--}
```
public abstract boolean getHangingPunctuation()
```


Określa, czy w akapicie używana jest wieszająca interpunkcja. Tylko do odczytu boolean.

**Zwraca:**
boolean
### getMarginLeft() {#getMarginLeft--}
```
public abstract float getMarginLeft()
```


Zwraca lewy margines w akapicie. Tylko do odczytu float.

**Zwraca:**
float
### getMarginRight() {#getMarginRight--}
```
public abstract float getMarginRight()
```


Zwraca prawy margines w akapicie. Tylko do odczytu float.

**Zwraca:**
float
### getIndent() {#getIndent--}
```
public abstract float getIndent()
```


Zwraca wcięcie pierwszej linii/odwieszenie akapitu. Odwieszenie może być określone wartościami ujemnymi. Tylko do odczytu float.

**Zwraca:**
float
### getDefaultTabSize() {#getDefaultTabSize--}
```
public abstract float getDefaultTabSize()
```


Zwraca domyślny rozmiar tabulacji. Tylko do odczytu float.

**Zwraca:**
float
### getTabs() {#getTabs--}
```
public abstract ITabEffectiveData[] getTabs()
```


Zwraca tabulacje akapitu. Tylko do odczytu ITabEffectiveData[].

**Zwraca:**
com.aspose.slides.ITabEffectiveData[]
### getFontAlignment() {#getFontAlignment--}
```
public abstract int getFontAlignment()
```


Zwraca wyrównanie czcionki w akapicie. Tylko do odczytu [FontAlignment](../../com.aspose.slides/fontalignment).

**Zwraca:**
int
### getDefaultPortionFormat() {#getDefaultPortionFormat--}
```
public abstract IPortionFormatEffectiveData getDefaultPortionFormat()
```


Zwraca domyślny format fragmentu w akapicie. Tylko do odczytu [IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata).

**Zwraca:**
[IPortionFormatEffectiveData](../../com.aspose.slides/iportionformateffectivedata)