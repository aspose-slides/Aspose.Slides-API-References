---
title: HtmlGenerator
second_title: Aspose.Slides Androidra a Java API hivatkozáson keresztül
description: HTML generátor.
type: docs
url: /hu/com.aspose.slides/htmlgenerator/
---
**Öröklés:**
java.lang.Object

**Minden megvalósított interfész:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

HTML-generátor.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Formázott HTML szöveget ad hozzá. |
| [addHtml(char[] html)](#addHtml-char---) | Formázott HTML szöveget ad hozzá. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Formázott HTML szöveget ad hozzá. |
| [addText(String text)](#addText-java.lang.String-) | Egyszerű szöveget ad a HTML fájlokhoz, a speciális karaktereket HTML entitásokkal helyettesítve. |
| [addText(char[] text)](#addText-char---) | Egyszerű szöveget ad a HTML fájlokhoz, a speciális karaktereket HTML entitásokkal helyettesítve. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Egyszerű szöveget ad a HTML fájlokhoz, a speciális karaktereket HTML entitásokkal helyettesítve. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Az attribútum értéket idézőjelek közé teszi, és hozzáadja a HTML fájlhoz. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Az attribútum értéket idézőjelek közé teszi, és hozzáadja a HTML fájlhoz. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Az attribútum értéket idézőjelek közé teszi, és hozzáadja a HTML fájlhoz. |
| [getSlideImageSize()](#getSlideImageSize--) | Visszaadja a dia kép méretét. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Visszaadja a mértékegységet, amelyben a dia kép mérete meg van adva. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Visszaadja a CSS kódot a mértékegységhez, amelyben a dia kép mérete meg van adva. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Visszaadja az előzőleg megjelenített dia indexét, vagy -1-et, ha az első dia jelenik meg. |
| [getSlideIndex()](#getSlideIndex--) | Visszaadja a jelenleg megjelenített dia indexét. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Visszaadja egy dia indexét, amely a jelenlegi dia után lesz megjelenítve, vagy -1-et, ha a jelenleg utolsó diát jeleníti meg. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Formázott HTML szöveget ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| html | java.lang.String | Hozzáadandó szöveg. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Formázott HTML szöveget ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| html | char[] | Hozzáadandó szöveg. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Formázott HTML szöveget ad hozzá.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| html | char[] | Hozzáadandó szöveg. |
| startIndex | int | A hozzáadandó rész kezdő indexe. |
| length | int | A hozzáadandó rész hossza. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Egyszerű szöveget ad a HTML fájlokhoz, a speciális karaktereket HTML entitásokkal helyettesítve. Sorvégek és szóközök nem kerülnek helyettesítésre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Hozzáadandó szöveg. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Egyszerű szöveget ad a HTML fájlokhoz, a speciális karaktereket HTML entitásokkal helyettesítve. Sorvégek és szóközök nem kerülnek helyettesítésre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | char[] | Hozzáadandó szöveg. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Egyszerű szöveget ad a HTML fájlokhoz, a speciális karaktereket HTML entitásokkal helyettesítve. Sorvégek és szóközök nem kerülnek helyettesítésre.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | char[] | Hozzáadandó szöveg. |
| startIndex | int | A hozzáadandó rész kezdő indexe. |
| length | int | A hozzáadandó rész hossza. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Az attribútum értéket idézőjelek közé teszi, és hozzáadja a HTML fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String | Attribútum érték karakterlánc. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Az attribútum értéket idézőjelek közé teszi, és hozzáadja a HTML fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char[] | Attribútum érték karakterlánc. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Az attribútum értéket idézőjelek közé teszi, és hozzáadja a HTML fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char[] | Attribútum érték karakterlánc. |
| startIndex | int | A hozzáadandó rész kezdő indexe. |
| length | int | A hozzáadandó rész hossza. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

Visszaadja a dia kép méretét. Csak olvasható [SizeF](../../com.aspose.slides.android/sizef).

**Visszatér:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Visszaadja a mértékegységet, amelyben a dia kép mérete meg van adva. Csak olvasható [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Visszatér:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Visszaadja a CSS kódot a mértékegységhez, amelyben a dia kép mérete meg van adva. Csak olvasható String.

**Visszatér:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Visszaadja az előzőleg megjelenített dia indexét, vagy -1-et, ha az első dia jelenik meg. Csak olvasható int.

**Visszatér:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Visszaadja a jelenleg megjelenített dia indexét. Csak olvasható int.

**Visszatér:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Visszaadja egy dia indexét, amely a jelenlegi dia után lesz megjelenítve, vagy -1-et, ha a jelenleg utolsó diát jeleníti meg. Csak olvasható int.

**Visszatér:**
int