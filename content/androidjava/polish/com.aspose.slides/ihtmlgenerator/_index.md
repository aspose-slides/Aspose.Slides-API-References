---
title: IHtmlGenerator
second_title: Aspose.Slides dla Androida za pośrednictwem referencji API Java
description: Generator HTML.
type: docs
url: /pl/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
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
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Zwraca jednostkę, w której określono rozmiar obrazu slajdu. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Zwraca kod CSS jednostki, w której określono rozmiar obrazu slajdu. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Zwraca indeks poprzednio renderowanego slajdu lub -1, jeśli renderowany jest pierwszy slajd. |
| [getSlideIndex()](#getSlideIndex--) | Zwraca indeks aktualnie renderowanego slajdu. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Zwraca indeks slajdu, który zostanie wyrenderowany po bieżącym slajdzie lub -1, jeśli obecnie renderowany jest ostatni slajd. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Dodaje sformatowany tekst HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| html | java.lang.String | Tekst do dodania. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Dodaje sformatowany tekst HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| html | char[] | Tekst do dodania. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Dodaje sformatowany tekst HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| html | char[] | Tekst do dodania. |
| startIndex | int | Początkowy indeks części do dodania. |
| length | int | Długość części do dodania. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Dodaje zwykły tekst do plików HTML, zamieniając znaki specjalne na encje HTML. Znaki końca linii i białe znaki nie są zamieniane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | java.lang.String | Tekst do dodania. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Dodaje zwykły tekst do plików HTML, zamieniając znaki specjalne na encje HTML. Znaki końca linii i białe znaki nie są zamieniane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | char[] | Tekst do dodania. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Dodaje zwykły tekst do plików HTML, zamieniając znaki specjalne na encje HTML. Znaki końca linii i białe znaki nie są zamieniane.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| text | char[] | Tekst do dodania. |
| startIndex | int | Początkowy indeks części do dodania. |
| length | int | Długość części do dodania. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Cytuje wartość atrybutu i dodaje ją do pliku HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | java.lang.String | Ciąg znaków wartości atrybutu. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Cytuje wartość atrybutu i dodaje ją do pliku HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char[] | Ciąg znaków wartości atrybutu. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Cytuje wartość atrybutu i dodaje ją do pliku HTML.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | char[] | Ciąg znaków wartości atrybutu. |
| startIndex | int | Początkowy indeks części do dodania. |
| length | int | Długość części do dodania. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

Zwraca rozmiar obrazu slajdu. Tylko do odczytu [SizeF](../../com.aspose.slides.android/sizef).

**Zwraca:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Zwraca jednostkę, w której określono rozmiar obrazu slajdu. Tylko do odczytu [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Zwraca:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Zwraca kod CSS jednostki, w której określono rozmiar obrazu slajdu. Tylko do odczytu String.

**Zwraca:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Zwraca indeks poprzednio renderowanego slajdu lub -1, jeśli renderowany jest pierwszy slajd. Tylko do odczytu int.

**Zwraca:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Zwraca indeks aktualnie renderowanego slajdu. Tylko do odczytu int.

**Zwraca:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Zwraca indeks slajdu, który zostanie wyrenderowany po bieżącym slajdzie lub -1, jeśli obecnie renderowany jest ostatni slajd. Tylko do odczytu int.

**Zwraca:**
int