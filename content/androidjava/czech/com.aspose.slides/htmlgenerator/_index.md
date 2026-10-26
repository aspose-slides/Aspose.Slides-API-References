---
title: HtmlGenerator
second_title: Aspose.Slides pro Android prostřednictvím reference Java API
description: Html generátor.
type: docs
url: /cs/com.aspose.slides/htmlgenerator/
---
**Dědičnost:**
java.lang.Object

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

Generátor HTML.
## Metody

| Metoda | Popis |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Přidá formátovaný HTML text. |
| [addHtml(char[] html)](#addHtml-char---) | Přidá formátovaný HTML text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Přidá formátovaný HTML text. |
| [addText(String text)](#addText-java.lang.String-) | Přidá prostý text do HTML souborů a nahradí speciální znaky HTML entity. |
| [addText(char[] text)](#addText-char---) | Přidá prostý text do HTML souborů a nahradí speciální znaky HTML entity. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Přidá prostý text do HTML souborů a nahradí speciální znaky HTML entity. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Uvozovky hodnoty atributu a přidá ji do HTML souboru. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Uvozovky hodnoty atributu a přidá ji do HTML souboru. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Uvozovky hodnoty atributu a přidá ji do HTML souboru. |
| [getSlideImageSize()](#getSlideImageSize--) | Vrací velikost obrázku snímku. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Vrací jednotku, ve které je velikost obrázku snímku zadána. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Vrací CSS kód jednotky, ve které je velikost obrázku snímku zadána. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Vrací index dříve vykresleného snímku nebo -1, pokud se vykresluje první snímek. |
| [getSlideIndex()](#getSlideIndex--) | Vrací index aktuálně vykreslovaného snímku. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud se právě vykresluje poslední snímek. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Přidá formátovaný HTML text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| html | java.lang.String | Text k přidání. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Přidá formátovaný HTML text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| html | char[] | Text k přidání. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Přidá formátovaný HTML text.

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

Přidá prostý text do HTML souborů a nahradí speciální znaky HTML entity. Zlomky řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k přidání. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Přidá prostý text do HTML souborů a nahradí speciální znaky HTML entity. Zlomky řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | char[] | Text k přidání. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Přidá prostý text do HTML souborů a nahradí speciální znaky HTML entity. Zlomky řádků a mezery nejsou nahrazeny.

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

Uvozovky hodnoty atributu a přidá ji do HTML souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String | Řetězec hodnoty atributu. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Uvozovky hodnoty atributu a přidá ji do HTML souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char[] | Řetězec hodnoty atributu. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Uvozovky hodnoty atributu a přidá ji do HTML souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char[] | Řetězec hodnoty atributu. |
| startIndex | int | Počáteční index části k přidání. |
| length | int | Délka části k přidání. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

Vrací velikost obrázku snímku. Pouze pro čtení [SizeF](../../com.aspose.slides.android/sizef).

**Návratová hodnota:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Vrací jednotku, ve které je velikost obrázku snímku zadána. Pouze pro čtení [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Návratová hodnota:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Vrací CSS kód jednotky, ve které je velikost obrázku snímku zadána. Pouze pro čtení String.

**Návratová hodnota:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Vrací index dříve vykresleného snímku nebo -1, pokud se vykresluje první snímek. Pouze pro čtení int.

**Návratová hodnota:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Vrací index aktuálně vykreslovaného snímku. Pouze pro čtení int.

**Návratová hodnota:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud se právě vykresluje poslední snímek. Pouze pro čtení int.

**Návratová hodnota:**
int