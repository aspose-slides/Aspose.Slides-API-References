---
title: PatternFormat
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um padrão para preencher uma forma.
type: docs
url: /pt/com.aspose.slides/patternformat/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IPatternFormat](../../com.aspose.slides/ipatternformat)
```
public final class PatternFormat extends PVIObject implements IPatternFormat
```

Representa um padrão para preencher uma forma.
## Métodos

| Método | Descrição |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getPatternStyle()](#getPatternStyle--) | Retorna ou define o estilo do padrão. |
| [setPatternStyle(byte value)](#setPatternStyle-byte-) | Retorna ou define o estilo do padrão. |
| [getForeColor()](#getForeColor--) | Retorna a cor de primeiro plano do padrão. |
| [getBackColor()](#getBackColor--) | Retorna a cor de fundo do padrão. |
| [getTile(Integer background, Integer foreground)](#getTile-java.lang.Integer-java.lang.Integer-) | Cria uma imagem de telha para o preenchimento de padrão com cores especificadas. |
| [getTile(Integer styleColor)](#getTile-java.lang.Integer-) | Cria uma imagem de telha para o preenchimento de padrão. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long
### getPatternStyle() {#getPatternStyle--}
```
public final byte getPatternStyle()
```

Retorna ou define o estilo do padrão. Leitura/gravação [PatternStyle](../../com.aspose.slides/patternstyle).

**Retorna:**
byte
### setPatternStyle(byte value) {#setPatternStyle-byte-}
```
public final void setPatternStyle(byte value)
```

Retorna ou define o estilo do padrão. Leitura/gravação [PatternStyle](../../com.aspose.slides/patternstyle).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | byte |  |

### getForeColor() {#getForeColor--}
```
public final IColorFormat getForeColor()
```

Retorna a cor de primeiro plano do padrão. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getBackColor() {#getBackColor--}
```
public final IColorFormat getBackColor()
```

Retorna a cor de fundo do padrão. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getTile(Integer background, Integer foreground) {#getTile-java.lang.Integer-java.lang.Integer-}
```
public final IImage getTile(Integer background, Integer foreground)
```

Cria uma imagem de telha para o preenchimento de padrão com cores especificadas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| background | java.lang.Integer | O java.lang.Integer de fundo para o padrão. |
| foreground | java.lang.Integer | O java.lang.Integer de primeiro plano para o padrão. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).
### getTile(Integer styleColor) {#getTile-java.lang.Integer-}
```
public final IImage getTile(Integer styleColor)
```

Cria uma imagem de telha para o preenchimento de padrão.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| styleColor | java.lang.Integer | O java.lang.Integer padrão |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).