---
title: MathBorderBoxFactory
second_title: Aspose.Slides para Referência da API Java
description: Permite criar uma caixa de borda matemática
type: docs
url: /pt/com.aspose.slides/mathborderboxfactory/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IMathBorderBoxFactory](../../com.aspose.slides/imathborderboxfactory)
```
public class MathBorderBoxFactory implements IMathBorderBoxFactory
```

Permite criar uma caixa de borda matemática

--------------------

Para compatibilidade COM
## Constructors

| Constructor | Description |
| --- | --- |
| [MathBorderBoxFactory()](#MathBorderBoxFactory--) |  |
## Methods

| Method | Description |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Cria uma caixa de borda matemática aplicando ao elemento |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Cria uma caixa de borda matemática aplicando ao elemento |
### MathBorderBoxFactory() {#MathBorderBoxFactory--}
```
public MathBorderBoxFactory()
```


### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element)
```


Cria uma caixa de borda matemática aplicando ao elemento

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático ao qual aplicar a caixa de borda |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - novo elemento de caixa de borda
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public final IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```


Cria uma caixa de borda matemática aplicando ao elemento

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático ao qual aplicar a caixa de borda |
| hideTop | boolean | Ocultar a borda superior |
| hideBottom | boolean | Ocultar a borda inferior |
| hideLeft | boolean | Ocultar a borda esquerda |
| hideRight | boolean | Ocultar a borda direita |
| strikethroughHorizontal | boolean | Riscado horizontal da caixa de borda |
| strikethroughVertical | boolean | Riscado vertical da caixa de borda |
| strikethroughBottomLeftToTopRight | boolean | Riscado da caixa de borda da parte inferior esquerda para a superior direita |
| strikethroughTopLeftToBottomRight | boolean | Riscado da caixa de borda da parte superior esquerda para a inferior direita |

**Returns:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - novo elemento de caixa de borda