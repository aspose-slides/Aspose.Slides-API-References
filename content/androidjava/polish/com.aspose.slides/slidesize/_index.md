---
title: SlideSize
second_title: Aspose.Slides dla Androida przy użyciu interfejsu API Java
description: Reprezentuje rozmiar i orientację slajdu.
type: docs
url: /pl/com.aspose.slides/slidesize/
---
**Dziedziczenie:**
java.lang.Object, com.aspose.slides.DomObject

**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.ISlideSize](../../com.aspose.slides/islidesize)
```
public class SlideSize extends DomObject<Presentation> implements ISlideSize
```

Reprezentuje rozmiar i orientację slajdu.
## Metody

| Metoda | Opis |
| --- | --- |
| [getSize()](#getSize--) | Pobiera wymiary slajdu w punktach. |
| [getType()](#getType--) | Pobiera typ rozmiaru slajdu. |
| [getOrientation()](#getOrientation--) | Pobiera lub ustawia orientację slajdu. |
| [setOrientation(int value)](#setOrientation-int-) | Pobiera lub ustawia orientację slajdu. |
| [setSize(int type, int scaleType)](#setSize-int-int-) | Ustawia rozmiar slajdu według typu i skaluje istniejącą zawartość. |
| [setSize(float width, float height, int scaleType)](#setSize-float-float-int-) | Ustawia wymiary slajdu eksplicytnie i skaluje istniejącą zawartość. |
### getSize() {#getSize--}
```
public final SizeF getSize()
```


Pobiera wymiary slajdu w punktach.

--------------------

Przypisanie nowej wartości resetuje właściwość \#getType.getType do [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) i ustawia \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Zwraca:**
[SizeF](../../com.aspose.slides.android/sizef)
### getType() {#getType--}
```
public final int getType()
```


Pobiera typ rozmiaru slajdu.

--------------------

Przypisanie dowolnej wartości innej niż [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dostosowuje \#getSize.getSize zgodnie z predefiniowanymi wymiarami, zachowując jednocześnie bieżącą \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int).

**Zwraca:**
int
### getOrientation() {#getOrientation--}
```
public final int getOrientation()
```


Pobiera lub ustawia orientację slajdu.

--------------------

Zmiana tej wartości zamienia szerokość i wysokość slajdu.

**Zwraca:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public final void setOrientation(int value)
```


Pobiera lub ustawia orientację slajdu.

--------------------

Zmiana tej wartości zamienia szerokość i wysokość slajdu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |

### setSize(int type, int scaleType) {#setSize-int-int-}
```
public final void setSize(int type, int scaleType)
```


Ustawia rozmiar slajdu według typu i skaluje istniejącą zawartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| type | int | Predefiniowany rozmiar slajdu do zastosowania. |
| scaleType | int | Tryb skalowania zawartości do użycia.

--------------------

Przypisanie dowolnej wartości innej niż [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) dostosowuje \#getSize.getSize w oparciu o wybrany typ, zachowując \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |

### setSize(float width, float height, int scaleType) {#setSize-float-float-int-}
```
public final void setSize(float width, float height, int scaleType)
```


Ustawia wymiary slajdu eksplicytnie i skaluje istniejącą zawartość.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| width | float | Nowa szerokość slajdu, w punktach. |
| height | float | Nowa wysokość slajdu, w punktach. |
| scaleType | int | Tryb skalowania zawartości do użycia.

--------------------

To resetuje właściwość \#getType.getType do [SlideSizeType.Custom](../../com.aspose.slides/slidesizetype\#Custom) i ustawia \#getOrientation.getOrientation/\#setOrientation(int).setOrientation(int). |