---
title: HtmlGenerator
second_title: Referência da API Java do Aspose.Slides para Android
description: Gerador HTML.
type: docs
url: /pt/com.aspose.slides/htmlgenerator/
---
**Herança:**  
java.lang.Object

**Todas as Interfaces Implementadas:**  
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)  
```
public final class HtmlGenerator implements IHtmlGenerator
```

Gerador HTML.

## Métodos

| Método | Descrição |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Adiciona texto HTML formatado. |
| [addHtml(char[] html)](#addHtml-char---) | Adiciona texto HTML formatado. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Adiciona texto HTML formatado. |
| [addText(String text)](#addText-java.lang.String-) | Adiciona texto simples aos arquivos HTML, substituindo caracteres especiais por entidades HTML. |
| [addText(char[] text)](#addText-char---) | Adiciona texto simples aos arquivos HTML, substituindo caracteres especiais por entidades HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Adiciona texto simples aos arquivos HTML, substituindo caracteres especiais por entidades HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Cita o valor do atributo e o adiciona ao arquivo HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Cita o valor do atributo e o adiciona ao arquivo HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Cita o valor do atributo e o adiciona ao arquivo HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Retorna o tamanho da imagem do slide. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Retorna a unidade em que o tamanho da imagem do slide é especificado. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Retorna um código CSS da unidade em que o tamanho da imagem do slide é especificado. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Retorna o índice do slide renderizado anteriormente ou -1 se o primeiro slide está sendo renderizado. |
| [getSlideIndex()](#getSlideIndex--) | Retorna o índice do slide que está sendo renderizado atualmente. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Retorna o índice de um slide que será renderizado após o slide atual ou -1 se o slide atual for o último a ser renderizado. |

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
public final SizeF getSlideImageSize()
```

Retorna o tamanho da imagem do slide. Somente leitura [SizeF](../../com.aspose.slides.android/sizef).

**Retorna:**
[SizeF](../../com.aspose.slides.android/sizef)

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

Retorna o índice do slide renderizado anteriormente ou -1 se o primeiro slide está sendo renderizado. Somente leitura int.

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

Retorna o índice de um slide que será renderizado após o slide atual ou -1 se o slide atual for o último a ser renderizado. Somente leitura int.

**Retorna:**
int