---
title: ITextFrameFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Objeto imutável que contém propriedades efetivas de formatação de quadro de texto.
type: docs
url: /pt/com.aspose.slides/itextframeformateffectivedata/
---```
public interface ITextFrameFormatEffectiveData
```

Objeto imutável que contém propriedades efetivas de formatação de quadro de texto.

--------------------

Esta interface é usada junto com a interface [ITextFrameFormat](../../com.aspose.slides/itextframeformat) para retornar valores efetivos de formatação com herança aplicada.
## Métodos

| Method | Description |
| --- | --- |
| [getTextStyle()](#getTextStyle--) | Retorna o estilo efetivo do texto. |
| [getMarginLeft()](#getMarginLeft--) | Retorna a margem esquerda (pontos) em um TextFrame. |
| [getMarginRight()](#getMarginRight--) | Retorna a margem direita (pontos) em um TextFrame. |
| [getMarginTop()](#getMarginTop--) | Retorna a margem superior (pontos) em um TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Retorna a margem inferior (pontos) em um TextFrame. |
| [getWrapText()](#getWrapText--) | Retorna se o texto está ajustado nas margens do TextFrame. |
| [getAnchoringType()](#getAnchoringType--) | Retorna o âncora vertical do texto em um TextFrame. |
| [getCenterText()](#getCenterText--) | Retorna se o texto deve ser centralizado horizontalmente na caixa. |
| [getTextVerticalType()](#getTextVerticalType--) | Retorna a orientação do texto. |
| [getAutofitType()](#getAutofitType--) | Retorna o modo de ajuste automático do texto. |
| [getColumnCount()](#getColumnCount--) | Especifica o número de colunas de texto no retângulo delimitador. |
| [getColumnSpacing()](#getColumnSpacing--) | Especifica o espaço entre colunas de texto na área de texto (em pontos). |
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

Retorna se o texto está ajustado nas margens do TextFrame. Somente leitura boolean.

**Retorna:**
boolean
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Retorna o âncora vertical do texto em um TextFrame. Somente leitura [TextAnchorType](../../com.aspose.slides/textanchortype).

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