---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Html generator.
type: docs
url: /hu/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

HTML generátor.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Formázott HTML szöveget ad hozzá. |
| [addHtml(char[] html)](#addHtml-char---) | Formázott HTML szöveget ad hozzá. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Formázott HTML szöveget ad hozzá. |
| [addText(String text)](#addText-java.lang.String-) | Egyszerű szöveget ad az html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve. |
| [addText(char[] text)](#addText-char---) | Egyszerű szöveget ad az html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Egyszerű szöveget ad az html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Idézőjelezni az attribútum értékét és hozzáadja a HTML fájlhoz. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Idézőjelezni az attribútum értékét és hozzáadja a HTML fájlhoz. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Idézőjelezni az attribútum értékét és hozzáadja a HTML fájlhoz. |
| [getSlideImageSize()](#getSlideImageSize--) | Visszaadja a dia kép méretét. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Visszaadja az egységet, amelyben a dia kép mérete meg van adva. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Visszaadja az egység CSS kódját, amelyben a dia kép mérete meg van adva. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Visszaadja az előzőleg renderelt dia indexét, vagy -1-et, ha az első dia kerül renderelésre. |
| [getSlideIndex()](#getSlideIndex--) | Visszaadja a jelenleg renderelt dia indexét. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Visszaadja annak a diának az indexét, amely a jelenlegi dia után kerül renderelésre, vagy -1-et, ha az utolsó diát rendereli. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```


Formázott HTML szöveget ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| html | java.lang.String | Hozzáadandó szöveg. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```


Formázott HTML szöveget ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| html | char[] | Hozzáadandó szöveg. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```


Formázott HTML szöveget ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| html | char[] | Hozzáadandó szöveg. |
| startIndex | int | A hozzáadandó rész kezdőindexe. |
| length | int | A hozzáadandó rész hossza. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```


Egyszerű szöveget ad az html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve. A sortöréseket és szóközöket nem helyettesítik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Hozzáadandó szöveg. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```


Egyszerű szöveget ad az html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve. A sortöréseket és szóközöket nem helyettesítik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | char[] | Hozzáadandó szöveg. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```


Egyszerű szöveget ad az html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve. A sortöréseket és szóközöket nem helyettesítik.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | char[] | Hozzáadandó szöveg. |
| startIndex | int | A hozzáadandó rész kezdőindexe. |
| length | int | A hozzáadandó rész hossza. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```


Idézőjelezni az attribútum értékét és hozzáadja a HTML fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String | Az attribútum értékének karakterlánca. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```


Idézőjelezni az attribútum értékét és hozzáadja a HTML fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char[] | Az attribútum értékének karakterlánca. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```


Idézőjelezni az attribútum értékét és hozzáadja a HTML fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char[] | Az attribútum értékének karakterlánca. |
| startIndex | int | A hozzáadandó rész kezdőindexe. |
| length | int | A hozzáadandó rész hossza. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```


Visszaadja a dia kép méretét. Csak olvasható [SizeF](../../com.aspose.slides.android/sizef).

**Visszatérési érték:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```


Visszaadja az egységet, amelyben a dia kép mérete meg van adva. Csak olvasható [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Visszatérési érték:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```


Visszaadja az egység CSS kódját, amelyben a dia kép mérete meg van adva. Csak olvasható String.

**Visszatérési érték:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```


Visszaadja az előzőleg renderelt dia indexét, vagy -1-et, ha az első dia kerül renderelésre. Csak olvasható int.

**Visszatérési érték:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```


Visszaadja a jelenleg renderelt dia indexét. Csak olvasható int.

**Visszatérési érték:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```


Visszaadja annak a diának az indexét, amely a jelenlegi dia után kerül renderelésre, vagy -1-et, ha az utolsó diát rendereli. Csak olvasható int.

**Visszatérési érték:**
int