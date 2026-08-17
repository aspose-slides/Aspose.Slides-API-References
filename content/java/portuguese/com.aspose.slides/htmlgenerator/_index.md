---
title: HtmlGenerator
second_title: Referência da API Aspose.Slides para Java
description: Gerador de HTML.
type: docs
url: /pt/com.aspose.slides/htmlgenerator/
---
**Herança:** java.lang.Object

**Todas as Interfaces Implementadas:** [com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator) ```
public final class HtmlGenerator implements IHtmlGenerator
```

Gerador HTML.
## Métodos

| Método | Descrição |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Adds formatted HTML text. |
| [addHtml(char[] html)](#addHtml-char---) | Adds formatted HTML text. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Adds formatted HTML text. |
| [addText(String text)](#addText-java.lang.String-) | Adds plain text to the html files, replacing special characters with html entities. |
| [addText(char[] text)](#addText-char---) | Adds plain text to the html files, replacing special characters with html entities. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Adds plain text to the html files, replacing special characters with html entities. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Quotes attribute value and adds it to the html file. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Quotes attribute value and adds it to the html file. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Quotes attribute value and adds it to the html file. |
| [getSlideImageSize()](#getSlideImageSize--) | Returns slide image size. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Returns a unit in which slide image size is specified. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Returns a css code of unit in which slide image size is specified. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Returns index of previously rendered slide or -1 if first slide is rendering. |
| [getSlideIndex()](#getSlideIndex--) | Returns index of currently rendering slide. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Returns index of a slide, which will be rendered after the current slide or -1 if currently rendering last slide. |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

Adiciona texto HTML formatado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| html | java.lang.String | Texto a ser adicionado. |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

Adiciona texto HTML formatado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| html | char[] | Texto a ser adicionado. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

Adiciona texto HTML formatado.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| html | char[] | Texto a ser adicionado. |
| startIndex | int | Índice inicial da porção a ser adicionada. |
| length | int | Comprimento da porção a ser adicionada. |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

Adiciona texto simples aos arquivos HTML, substituindo caracteres especiais por entidades HTML. Quebras de linha e espaços em branco não são substituídos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | java.lang.String | Texto a ser adicionado. |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

Adiciona texto simples aos arquivos HTML, substituindo caracteres especiais por entidades HTML. Quebras de linha e espaços em branco não são substituídos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | char[] | Texto a ser adicionado. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

Adiciona texto simples aos arquivos HTML, substituindo caracteres especiais por entidades HTML. Quebras de linha e espaços em branco não são substituídos.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| text | char[] | Texto a ser adicionado. |
| startIndex | int | Índice inicial da porção a ser adicionada. |
| length | int | Comprimento da porção a ser adicionada. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

Cita o valor do atributo e o adiciona ao arquivo HTML.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | java.lang.String | Cadeia de caracteres do valor do atributo. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

Cita o valor do atributo e o adiciona ao arquivo HTML.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char[] | Cadeia de caracteres do valor do atributo. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

Cita o valor do atributo e o adiciona ao arquivo HTML.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | char[] | Cadeia de caracteres do valor do atributo. |
| startIndex | int | Índice inicial da porção a ser adicionada. |
| length | int | Comprimento da porção a ser adicionada. |

### getSlideImageSize() {#getSlideImageSize--}
```
public final Dimension2D getSlideImageSize()
```

Retorna o tamanho da imagem do slide. Somente leitura java.awt.geom.Dimension2D.

**Retorna:**
java.awt.geom.Dimension2D
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

Retorna a unidade em que o tamanho da imagem do slide é especificado. Somente leitura [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Retorna:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

Retorna um código CSS da unidade em que o tamanho da imagem do slide é especificado. Somente leitura String.

**Retorna:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

Retorna o índice do slide anteriormente renderizado ou -1 se o primeiro slide está sendo renderizado. Somente leitura int.

**Retorna:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

Retorna o índice do slide que está sendo renderizado atualmente. Somente leitura int.

**Retorna:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

Retorna o índice de um slide que será renderizado após o slide atual ou -1 se o slide atual for o último. Somente leitura int.

**Retorna:**
int