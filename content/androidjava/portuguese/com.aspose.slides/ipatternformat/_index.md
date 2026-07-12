---
title: IPatternFormat
second_title: Aspose.Slides para Android via Referência da API Java
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
| [getPatternStyle()](#getPatternStyle--) | Returns or sets the pattern style. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Returns or sets the pattern style. |
| [getForeColor()](#getForeColor--) | Returns the foreground pattern color. |
| [getBackColor()](#getBackColor--) | Returns the background pattern color. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Creates a tile image for the pattern fill with a specified colors. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Creates a tile image for the pattern fill. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Obtém ou define o estilo do padrão. Leitura/escrita [PatternStyle](../../com.aspose.slides/patternstyle).

**Retorna:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public abstract void setPatternStyle(byte value)
```

Obtém ou define o estilo do padrão. Leitura/escrita [PatternStyle](../../com.aspose.slides/patternstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |
### getForeColor() {#getForeColor--}
```
public abstract IColorFormat getForeColor()
```

Retorna a cor de primeiro plano do padrão. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public abstract IColorFormat getBackColor()
```

Retorna a cor de fundo do padrão. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTile(Integer background, Integer foreground)
```

Cria uma imagem de ladrilho para o preenchimento do padrão com cores especificadas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| background | java.lang.Integer | O java.lang.Integer de fundo para o padrão. |
| foreground | java.lang.Integer | O java.lang.Integer de primeiro plano para o padrão. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Ladrilho android.graphics.Bitmap.
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public abstract IImage getTile(Integer styleColor)
```

Cria uma imagem de ladrilho para o preenchimento do padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| styleColor | java.lang.Integer | O java.lang.Integer padrão, definido no objeto StyleEx de ShapeEx. As cores do preenchimento podem depender disso. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Ladrilho android.graphics.Bitmap.