---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Android via Java API Reference
description: Objeto imutável que contém propriedades efetivas de preenchimento de padrão.
type: docs
url: /pt/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Objeto imutável que contém propriedades efetivas de preenchimento de padrão.

--------------------

Esta interface é usada como parte de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) e [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Métodos

| Method | Description |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Retorna o estilo do padrão. |
| [getForeColor()](#getForeColor--) | Retorna a cor de primeiro plano do padrão. |
| [getBackColor()](#getBackColor--) | Retorna a cor de fundo do padrão. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Cria uma imagem de ladrilho para o preenchimento de padrão com cores especificadas. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Retorna o estilo do padrão. Somente leitura [PatternStyle](../../com.aspose.slides/patternstyle).

**Retorna:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```

Retorna a cor de primeiro plano do padrão. Somente leitura java.lang.Integer.

**Retorna:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```

Retorna a cor de fundo do padrão. Somente leitura java.lang.Integer.

**Retorna:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```

Cria uma imagem de ladrilho para o preenchimento de padrão com cores especificadas.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| background | java.lang.Integer | O java.lang.Integer de fundo para o padrão. |
| foreground | java.lang.Integer | O java.lang.Integer de primeiro plano para o padrão. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Ladrilho [IImage](../../com.aspose.slides/iimage).