---
title: IHtmlGenerator
second_title: Aspose.Slides for Java API Reference
description: Html generátor.
type: docs
url: /cs/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Html generátor.
## Metody

| Metoda | Popis |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Přidává formátovaný HTML text. |
| [addHtml(char[] html)](#addHtml-char---) | Přidává formátovaný HTML text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Přidává formátovaný HTML text. |
| [addText(String text)](#addText-java.lang.String-) | Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. |
| [addText(char[] text)](#addText-char---) | Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Uvozkovává hodnotu atributu a přidává ji do souboru HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Uvozkovává hodnotu atributu a přidává ji do souboru HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Uvozkovává hodnotu atributu a přidává ji do souboru HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Vrací velikost obrázku snímku. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Vrací jednotku, ve které je velikost obrázku snímku specifikována. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Vrací CSS kód jednotky, ve které je velikost obrázku snímku specifikována. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Vrací index předchozího vykresleného snímku nebo -1, pokud se vykresluje první snímek. |
| [getSlideIndex()](#getSlideIndex--) | Vrací index aktuálně vykreslovaného snímku. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud je aktuálně vykreslen poslední snímek. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Přidává formátovaný HTML text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| html | java.lang.String | Text k přidání. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Přidává formátovaný HTML text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| html | char[] | Text k přidání. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Přidává formátovaný HTML text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| html | char[] | Text k přidání. |
| startIndex | int | Počáteční index části k přidání. |
| length | int | Délka části k přidání. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. Zalomení řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k přidání. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. Zalomení řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | char[] | Text k přidání. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. Zalomení řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | char[] | Text k přidání. |
| startIndex | int | Počáteční index části k přidání. |
| length | int | Délka části k přidání. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Uvozkovává hodnotu atributu a přidává ji do souboru HTML.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String | Řetězec hodnoty atributu. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Uvozkovává hodnotu atributu a přidává ji do souboru HTML.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char[] | Řetězec hodnoty atributu. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Uvozkovává hodnotu atributu a přidává ji do souboru HTML.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char[] | Řetězec hodnoty atributu. |
| startIndex | int | Počáteční index části k přidání. |
| length | int | Délka části k přidání. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract Dimension2D getSlideImageSize()
```

Vrací velikost obrázku snímku. Pouze ke čtení java.awt.geom.Dimension2D.

**Vrací:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Vrací jednotku, ve které je velikost obrázku snímku specifikována. Pouze ke čtení [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Vrací:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Vrací CSS kód jednotky, ve které je velikost obrázku snímku specifikována. Pouze ke čtení String.

**Vrací:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Vrací index předchozího vykresleného snímku nebo -1, pokud se vykresluje první snímek. Pouze ke čtení int.

**Vrací:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Vrací index aktuálně vykreslovaného snímku. Pouze ke čtení int.

**Vrací:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud je aktuálně vykreslen poslední snímek. Pouze ke čtení int.

**Vrací:**
int