---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
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
| [addHtml(String html)](#addHtml-java.lang.String-) | Přidá formátovaný HTML text. |
| [addHtml(char[] html)](#addHtml-char---) | Přidá formátovaný HTML text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Přidá formátovaný HTML text. |
| [addText(String text)](#addText-java.lang.String-) | Přidá prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. |
| [addText(char[] text)](#addText-char---) | Přidá prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Přidá prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Oquote hodnotu atributu a přidá ji do souboru HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Oquote hodnotu atributu a přidá ji do souboru HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Oquote hodnotu atributu a přidá ji do souboru HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Vrací velikost obrázku snímku. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Vrací jednotku, ve které je velikost obrázku snímku určena. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Vrací CSS kód jednotky, ve které je velikost obrázku snímku určena. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Vrací index předchozího vykresleného snímku nebo -1, pokud se vykresluje první snímek. |
| [getSlideIndex()](#getSlideIndex--) | Vrací index aktuálně vykreslovaného snímku. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud je právě vykreslován poslední snímek. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```


Přidá formátovaný HTML text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| html | java.lang.String | Text k přidání. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```


Přidá formátovaný HTML text.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| html | char[] | Text k přidání. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
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
public abstract void addText(String text)
```


Přidá prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. Zalomení řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | java.lang.String | Text k přidání. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```


Přidá prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. Zalomení řádků a mezery nejsou nahrazeny.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| text | char[] | Text k přidání. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```


Přidá prostý text do souborů HTML, nahrazující speciální znaky HTML entitami. Zalomení řádků a mezery nejsou nahrazeny.

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


Oquote hodnotu atributu a přidá ji do souboru HTML.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String | Řetězec hodnoty atributu. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```


Oquote hodnotu atributu a přidá ji do souboru HTML.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char[] | Řetězec hodnoty atributu. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```


Oquote hodnotu atributu a přidá ji do souboru HTML.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | char[] | Řetězec hodnoty atributu. |
| startIndex | int | Počáteční index části k přidání. |
| length | int | Délka části k přidání. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```


Vrací velikost obrázku snímku. Pouze pro čtení [SizeF](../../com.aspose.slides.android/sizef).

**Návratová hodnota:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```


Vrací jednotku, ve které je velikost obrázku snímku určena. Pouze pro čtení [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Návratová hodnota:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```


Vrací CSS kód jednotky, ve které je velikost obrázku snímku určena. Pouze pro čtení String.

**Návratová hodnota:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```


Vrací index předchozího vykresleného snímku nebo -1, pokud se vykresluje první snímek. Pouze pro čtení int.

**Návratová hodnota:**
int
### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```


Vrací index aktuálně vykreslovaného snímku. Pouze pro čtení int.

**Návratová hodnota:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```


Vrací index snímku, který bude vykreslen po aktuálním snímku, nebo -1, pokud je právě vykreslován poslední snímek. Pouze pro čtení int.

**Návratová hodnota:**
int