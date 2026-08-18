---
title: IDrawingGuide
second_title: Aspose.Slides for Java API Reference
description: Reprezentuje regulowaną prowadnicę rysowania.
type: docs
url: /pl/com.aspose.slides/idrawingguide/
---```
public interface IDrawingGuide
```

Reprezentuje regulowaną prowadnicę rysowania.
## Metody

| Metoda | Opis |
| --- | --- |
| [getOrientation()](#getOrientation--) | Zwraca lub ustawia orientację prowadnicy rysowania. |
| [setOrientation(byte value)](#setOrientation-byte-) | Zwraca lub ustawia orientację prowadnicy rysowania. |
| [getPosition()](#getPosition--) | Zwraca lub ustawia położenie prowadnicy rysowania w punktach od górnego lewego rogu slajdu. |
| [setPosition(float value)](#setPosition-float-) | Zwraca lub ustawia położenie prowadnicy rysowania w punktach od górnego lewego rogu slajdu. |
| [getColor()](#getColor--) | Zwraca lub ustawia kolor prowadnicy rysowania. |
| [setColor(Color value)](#setColor-java.awt.Color-) | Zwraca lub ustawia kolor prowadnicy rysowania. |
### getOrientation() {#getOrientation--}
```
public abstract byte getOrientation()
```


Zwraca lub ustawia orientację prowadnicy rysowania. Odczyt/zapis [Orientation](../../com.aspose.slides/orientation).

**Zwraca:**
byte
### setOrientation(byte value) {#setOrientation-byte-}
```
public abstract void setOrientation(byte value)
```


Zwraca lub ustawia orientację prowadnicy rysowania. Odczyt/zapis [Orientation](../../com.aspose.slides/orientation).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getPosition() {#getPosition--}
```
public abstract float getPosition()
```


Zwraca lub ustawia położenie prowadnicy rysowania w punktach od górnego lewego rogu slajdu. Odczyt/zapis float.

--------------------

Typowy zakres wartości wynosi od zera do wysokości slajdu dla prowadnicy poziomej i od zera do szerokości slajdu dla prowadnicy pionowej.

**Zwraca:**
float
### setPosition(float value) {#setPosition-float-}
```
public abstract void setPosition(float value)
```


Zwraca lub ustawia położenie prowadnicy rysowania w punktach od górnego lewego rogu slajdu. Odczyt/zapis float.

--------------------

Typowy zakres wartości wynosi od zera do wysokości slajdu dla prowadnicy poziomej i od zera do szerokości slajdu dla prowadnicy pionowej.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getColor() {#getColor--}
```
public abstract Color getColor()
```


Zwraca lub ustawia kolor prowadnicy rysowania. Odczyt/zapis java.awt.Color.

**Zwraca:**
java.awt.Color
### setColor(Color value) {#setColor-java.awt.Color-}
```
public abstract void setColor(Color value)
```


Zwraca lub ustawia kolor prowadnicy rysowania. Odczyt/zapis java.awt.Color.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.awt.Color |  |