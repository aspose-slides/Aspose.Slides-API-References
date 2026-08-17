---
title: IPatternFormat
second_title: Aspose.Slides for Java API Reference
description: Representa um padrão para preencher uma forma.
type: docs
url: /pt/com.aspose.slides/ipatternformat/
---```
public interface IPatternFormat
```

Representa um padrão para preencher uma forma.
## Métodos

| Método | Descrição |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Obtém ou define o estilo do padrão. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Obtém ou define o estilo do padrão. |
| [getForeColor()](#getForeColor--) | Retorna a cor do padrão de primeiro plano. |
| [getBackColor()](#getBackColor--) | Retorna a cor de fundo do padrão. |
| [getTile(Color background, Color foreground)](#getTile-java.awt.Color-java.awt.Color-) | Cria uma imagem de bloco para o preenchimento de padrão com cores especificadas. |
| [getTile(Color styleColor)](#getTile-java.awt.Color-) | Cria uma imagem de bloco para o preenchimento de padrão. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Obtém ou define o estilo do padrão. Leitura/gravação [PatternStyle](../../com.aspose.slides/patternstyle).

**Retorna:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```


Obtém ou define o estilo do padrão. Leitura/gravação [PatternStyle](../../com.aspose.slides/patternstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```


Retorna a cor do padrão de primeiro plano. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```


Retorna a cor de fundo do padrão. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Color background, Color foreground) {#getTile-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTile(Color background, Color foreground)
```


Cria uma imagem de bloco para o preenchimento de padrão com cores especificadas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| background | java.awt.Color | A cor de fundo java.awt.Color para o padrão. |
| foreground | java.awt.Color | A cor de primeiro plano java.awt.Color para o padrão. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.
### getTile(Color styleColor) {#getTile-java.awt.Color-}
```
public abstract IImage getTile(Color styleColor)
```


Cria uma imagem de bloco para o preenchimento de padrão.

**Parâmetro:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| styleColor | java.awt.Color | A cor java.awt.Color padrão, definida no objeto StyleEx de ShapeEx. As cores de preenchimento podem depender disso. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Tile java.awt.image.BufferedImage.