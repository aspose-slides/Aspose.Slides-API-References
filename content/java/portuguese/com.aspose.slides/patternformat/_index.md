---
title: PatternFormat
second_title: Referência da API Aspose.Slides para Java
description: Representa um padrão para preencher uma forma.
type: docs
url: /pt/com.aspose.slides/patternformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**All Implemented Interfaces:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Representa um padrão para preencher uma forma.
## Methods

| Method | Description |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Retorna ou define o estilo do padrão. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Retorna ou define o estilo do padrão. |
| [getForeColor()](#getForeColor--) | Retorna a cor do padrão de primeiro plano. |
| [getBackColor()](#getBackColor--) | Retorna a cor do padrão de plano de fundo. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Cria uma imagem de bloco para o preenchimento de padrão com cores especificadas. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Cria uma imagem de bloco para o preenchimento de padrão. |
### getVersion() {#getVersion--}
```
public long getVersion()
```


Versão. Somente leitura long.

**Returns:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```


Retorna ou define o estilo do padrão. Leitura/gravação [PatternStyle](../../com.aspose.slides/patternstyle).

**Returns:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```


Retorna ou define o estilo do padrão. Leitura/gravação [PatternStyle](../../com.aspose.slides/patternstyle).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```


Retorna a cor do padrão de primeiro plano. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```


Retorna a cor do padrão de plano de fundo. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public final IImage getTile(Color background, Color foreground)
```


Cria uma imagem de bloco para o preenchimento de padrão com cores especificadas.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.awt.Color | A cor java.awt.Color de plano de fundo para o padrão. |
| foreground | java.awt.Color | A cor java.awt.Color de primeiro plano para o padrão. |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bloco [IImage](../../com.aspose.slides/iimage).
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public final IImage getTile(Color styleColor)
```


Cria uma imagem de bloco para o preenchimento de padrão.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | java.awt.Color | A cor java.awt.Color padrão |

**Returns:**
[IImage](../../com.aspose.slides/iimage) - Bloco [IImage](../../com.aspose.slides/iimage).