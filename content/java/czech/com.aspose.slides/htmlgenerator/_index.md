---
title: HtmlGenerator
second_title: Aspose.Slides pro Java referenční příručka API
description: Generátor HTML.
type: docs
url: /cs/com.aspose.slides/htmlgenerator/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Generátor HTML.
## Metody

| Metoda | Popis |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Přidává formátovaný HTML text. |
| [addHtml(char[] html)](#addHtml-char---) | Přidává formátovaný HTML text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Přidává formátovaný HTML text. |
| [addText(String text)](#addText-java.lang.String-) | Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entity. |
| [addText(char[] text)](#addText-char---) | Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entity. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entity. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Označí hodnotu atributu uvozovkami a přidá ji do souboru HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Označí hodnotu atributu uvozovkami a přidá ji do souboru HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Označí hodnotu atributu uvozovkami a přidá ji do souboru HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Vrací velikost obrázku snímku. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Vrací jednotku, ve které je velikost obrázku snímku specifikována. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Vrací CSS kód jednotky, ve které je velikost obrázku snímku specifikována. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Vrací index předchozího vykresleného snímku nebo -1, pokud je vykreslován první snímek. |
| [getSlideIndex()](#getSlideIndex--) | Vrací index aktuálně vykreslovaného snímku. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud je aktuální snímek poslední. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Přidává formátovaný HTML text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| html | java.lang.String | Text k přidání. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Přidává formátovaný HTML text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| html | char[] | Text k přidání. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
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
public final void addText(String text)
```

Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entity. Zalamování řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k přidání. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entity. Zalamování řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | char[] | Text k přidání. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Přidává prostý text do souborů HTML, nahrazující speciální znaky HTML entity. Zalamování řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | char[] | Text k přidání. |
| startIndex | int | Počáteční index části k přidání. |
| length | int | Délka části k přidání. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Označí hodnotu atributu uvozovkami a přidá ji do souboru HTML.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String | Řetězec s hodnotou atributu. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Označí hodnotu atributu uvozovkami a přidá ji do souboru HTML.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char[] | Řetězec s hodnotou atributu. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Označí hodnotu atributu uvozovkami a přidá ji do souboru HTML.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char[] | Řetězec s hodnotou atributu. |
| startIndex | int | Počáteční index části k přidání. |
| length | int | Délka části k přidání. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

Vrací velikost obrázku snímku. Pouze pro čtení java.awt.geom.Dimension2D.

**Vrací:**
java.awt.geom.Dimension2D

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Vrací jednotku, ve které je velikost obrázku snímku specifikována. Pouze pro čtení [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Vrací:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Vrací CSS kód jednotky, ve které je velikost obrázku snímku specifikována. Pouze pro čtení String.

**Vrací:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Vrací index předchozího vykresleného snímku nebo -1, pokud je vykreslován první snímek. Pouze pro čtení int.

**Vrací:**
int

### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Vrací index aktuálně vykreslovaného snímku. Pouze pro čtení int.

**Vrací:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud je aktuální snímek poslední. Pouze pro čtení int.

**Vrací:**
int