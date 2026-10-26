---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: HTML generátor.
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
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Idézőjelezett attribútumértéket ad az html fájlhoz. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Idézőjelezett attribútumértéket ad az html fájlhoz. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Idézőjelezett attribútumértéket ad az html fájlhoz. |
| [getSlideImageSize()](#getSlideImageSize--) | Diaképméretet ad vissza. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Visszaadja az egységet, amiben a diaképméret meg van adva. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Visszaadja az egység css kódját, amiben a diaképméret meg van adva. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Visszaadja az előzőleg renderelt dia indexét, vagy -1, ha az első dia renderelése folyik. |
| [getSlideIndex()](#getSlideIndex--) | Visszaadja a jelenleg renderelt dia indexét. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Visszaadja a dia indexét, amely a jelenlegi dia után lesz renderelve, vagy -1, ha a jelenlegi dia az utolsó. |

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

Egyszerű szöveget ad az html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve. Sortöréseket és üres karaktereket nem helyettesíti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | java.lang.String | Hozzáadandó szöveg. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Egyszerű szöveget ad az html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve. Sortöréseket és üres karaktereket nem helyettesíti.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| text | char[] | Hozzáadandó szöveg. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Egyszerű szöveget ad az html fájlokhoz, a speciális karaktereket html entitásokkal helyettesítve. Sortöréseket és üres karaktereket nem helyettesíti.

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

Idézőjelezett attribútumértéket ad az html fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String | Attribútumérték karakterlánc. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Idézőjelezett attribútumértéket ad az html fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char[] | Attribútumérték karakterlánc. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Idézőjelezett attribútumértéket ad az html fájlhoz.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | char[] | Attribútumérték karakterlánc. |
| startIndex | int | A hozzáadandó rész kezdőindexe. |
| length | int | A hozzáadandó rész hossza. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

Diaképméretet ad vissza. Csak olvasható java.awt.geom.Dimension2D.

**Visszatérési érték:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Visszaadja az egységet, amiben a diaképméret meg van adva. Csak olvasható [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Visszatérési érték:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Visszaadja az egység css kódját, amiben a diaképméret meg van adva. Csak olvasható String.

**Visszatérési érték:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Visszaadja az előzőleg renderelt dia indexét, vagy -1, ha az első dia renderelése folyik. Csak olvasható int.

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

Visszaadja a dia indexét, amely a jelenlegi dia után lesz renderelve, vagy -1, ha a jelenlegi dia az utolsó. Csak olvasható int.

**Visszatérési érték:**
int