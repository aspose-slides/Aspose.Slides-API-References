---
title: HtmlGenerator
second_title: Aspose.Slides dla Androida - odniesienie API Java
description: Generator HTML.
type: docs
url: /pl/com.aspose.slides/htmlgenerator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Generator HTML.
## Metody

| Metoda | Opis |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Dodaje sformatowany tekst HTML. |
| [addHtml(char[] html)](#addHtml-char---) | Dodaje sformatowany tekst HTML. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Dodaje sformatowany tekst HTML. |
| [addText(String text)](#addText-java.lang.String-) | Dodaje zwykły tekst do plików HTML, zamieniając znaki specjalne na encje HTML. |
| [addText(char[] text)](#addText-char---) | Dodaje zwykły tekst do plików HTML, zamieniając znaki specjalne na encje HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Dodaje zwykły tekst do plików HTML, zamieniając znaki specjalne na encje HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Cytuje wartość atrybutu i dodaje ją do pliku HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Cytuje wartość atrybutu i dodaje ją do pliku HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Cytuje wartość atrybutu i dodaje ją do pliku HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Zwraca rozmiar obrazu slajdu. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Zwraca jednostkę, w której określony jest rozmiar obrazu slajdu. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Zwraca kod CSS jednostki, w której określony jest rozmiar obrazu slajdu. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Zwraca indeks poprzednio renderowanego slajdu lub -1, jeśli renderowany jest pierwszy slajd. |
| [getSlideIndex()](#getSlideIndex--) | Zwraca indeks aktualnie renderowanego slajdu. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Zwraca indeks slajdu, który zostanie wyrenderowany po bieżącym slajdzie lub -1, jeśli aktualnie renderowany jest ostatni slajd. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```


Dodaje sformatowany tekst HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| html | java.lang.String | Tekst do dodania. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```


Dodaje sformatowany tekst HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| html | char[] | Tekst do dodania. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```


Dodaje sformatowany tekst HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| html | char[] | Tekst do dodania. |
| startIndex | int | Indeks początkowy części do dodania. |
| length | int | Długość części do dodania. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```


Dodaje zwykły tekst do plików HTML, zamieniając znaki specjalne na encje HTML. Znaki końca linii i białe znaki nie są zamieniane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do dodania. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```


Dodaje zwykły tekst do plików HTML, zamieniając znaki specjalne na encje HTML. Znaki końca linii i białe znaki nie są zamieniane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | char[] | Tekst do dodania. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```


Dodaje zwykły tekst do plików HTML, zamieniając znaki specjalne na encje HTML. Znaki końca linii i białe znaki nie są zamieniane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | char[] | Tekst do dodania. |
| startIndex | int | Indeks początkowy części do dodania. |
| length | int | Długość części do dodania. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```


Cytuje wartość atrybutu i dodaje ją do pliku HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String | Ciąg wartości atrybutu. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```


Cytuje wartość atrybutu i dodaje ją do pliku HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char[] | Ciąg wartości atrybutu. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```


Cytuje wartość atrybutu i dodaje ją do pliku HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char[] | Ciąg wartości atrybutu. |
| startIndex | int | Indeks początkowy części do dodania. |
| length | int | Długość części do dodania. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```


Zwraca rozmiar obrazu slajdu. Tylko do odczytu [SizeF](../../com.aspose.slides.android/sizef).

**Zwraca:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```


Zwraca jednostkę, w której określony jest rozmiar obrazu slajdu. Tylko do odczytu [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Zwraca:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```


Zwraca kod CSS jednostki, w której określony jest rozmiar obrazu slajdu. Tylko do odczytu String.

**Zwraca:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```


Zwraca indeks poprzednio renderowanego slajdu lub -1, jeśli renderowany jest pierwszy slajd. Tylko do odczytu int.

**Zwraca:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```


Zwraca indeks aktualnie renderowanego slajdu. Tylko do odczytu int.

**Zwraca:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```


Zwraca indeks slajdu, który zostanie wyrenderowany po bieżącym slajdzie lub -1, jeśli aktualnie renderowany jest ostatni slajd. Tylko do odczytu int.

**Zwraca:**
int