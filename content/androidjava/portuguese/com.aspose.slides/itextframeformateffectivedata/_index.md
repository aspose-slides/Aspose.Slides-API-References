---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides para Android via Referência de API Java
description: Immutable object which contains effective text frame formatting properties.
type: docs
url: /pt/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Objeto imutável que contém propriedades de formatação efetiva de moldura de texto.

--------------------

Esta interface é usada juntamente com a interface [ITextFrameFormat](../../com.aspose.slides/itextframeformat) para devolver valores de formatação efetiva com herança aplicada.
## Métodos

| Método | Descrição |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Returns effective text's style. |
| [getMarginLeft()](#getMarginLeft--) | Returns the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | Returns if text is wrapped at TextFrame's margins. |
| [getAnchoringType()](#getAnchoringType--) | Returns vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | Returns if text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Returns text orientation. |
| [getAutofitType()](#getAutofitType--) | Returns text autofit mode. |
| [getColumnCount()](#getColumnCount--) | Specifies the number of columns of text in the bounding rectangle. |
| [getColumnSpacing()](#getColumnSpacing--) | Specifies the space between text columns in the text area (in points). |
### getTextStyle() {#getTextStyle--}
```
public abstract ITextStyleEffectiveData getTextStyle()
```

Retorna o estilo efetivo do texto. Somente leitura [ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata).

**Retorna:**
[ITextStyleEffectiveData](../../com.aspose.slides/itextstyleeffectivedata)
### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Retorna a margem esquerda (pontos) em um TextFrame. Somente leitura double.

**Retorna:**
double
### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Retorna a margem direita (pontos) em um TextFrame. Somente leitura double.

**Retorna:**
double
### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Retorna a margem superior (pontos) em um TextFrame. Somente leitura double.

**Retorna:**
double
### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Retorna a margem inferior (pontos) em um TextFrame. Somente leitura double.

**Retorna:**
double
### getWrapText() {#getWrapText--}
```
public abstract boolean getWrapText()
```

Retorna se o texto é ajustado nas margens do TextFrame. Somente leitura boolean.

**Retorna:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Retorna o ancoramento vertical do texto em um TextFrame. Somente leitura [TextAnchorType](../../com.aspose.slides/textanchortype).

**Retorna:**
byte
### getCenterText() {#getCenterText--}
```
public abstract boolean getCenterText()
```

Retorna se o texto deve ser centralizado horizontalmente na caixa. Somente leitura boolean.

**Retorna:**
boolean
### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Retorna a orientação do texto. Somente leitura [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Retorna:**
byte
### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Retorna o modo de ajuste automático do texto. Somente leitura [TextAutofitType](../../com.aspose.slides/textautofittype).

**Retorna:**
byte
### getColumnCount() {#getColumnCount--}
```
public abstract int getColumnCount()
```

Especifica o número de colunas de texto no retângulo delimitador. Somente leitura int.

**Retorna:**
int
### getColumnSpacing() {#getColumnSpacing--}
```
public abstract float getColumnSpacing()
```

Especifica o espaço entre colunas de texto na área de texto (em pontos). Somente leitura float.

**Retorna:**
float