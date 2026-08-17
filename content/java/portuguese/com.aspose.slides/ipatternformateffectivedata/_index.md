---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Immutable object which contains effective pattern filling properties.
type: docs
url: /pt/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Objeto imutável que contém propriedades efetivas de preenchimento de padrão.

--------------------

Esta interface é usada como parte de [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) e [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Métodos

| Método | Descrição |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Retorna o estilo do padrão. |
| [getForeColor()](#getForeColor--) | Retorna a cor de primeiro plano do padrão. |
| [getBackColor()](#getBackColor--) | Retorna a cor de plano de fundo do padrão. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Cria uma imagem de ladrilho para o preenchimento de padrão com cores específicas. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Retorna o estilo do padrão. Somente leitura [PatternStyle](../../com.aspose.slides/patternstyle).

**Retorna:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```


Retorna a cor de primeiro plano do padrão. Somente leitura java.awt.Color.

**Retorna:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```


Retorna a cor de plano de fundo do padrão. Somente leitura java.awt.Color.

**Retorna:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```


Cria uma imagem de ladrilho para o preenchimento de padrão com cores específicas.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| background | java.awt.Color | A cor de plano de fundo java.awt.Color para o padrão. |
| foreground | java.awt.Color | A cor de primeiro plano java.awt.Color para o padrão. |

**Retorna:**
[IImage](../../com.aspose.slides/iimage) - Ladrilho [IImage](../../com.aspose.slides/iimage).