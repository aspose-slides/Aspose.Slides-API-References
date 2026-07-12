---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create a math border box
type: docs
url: /pt/com.aspose.slides/imathborderboxfactory/
---```
public interface IMathBorderBoxFactory
```

Permite criar uma caixa de borda matemática

--------------------

Para compatibilidade COM
## Métodos

| Método | Descrição |
| --- | --- |
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Create a math border box by applying to the element |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Create a math border box by applying to the element |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Cria uma caixa de borda matemática aplicando ao elemento

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático para aplicar caixa de borda |

**Retorna:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - novo elemento de caixa de borda
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Cria uma caixa de borda matemática aplicando ao elemento

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático para aplicar caixa de borda |
| hideTop | boolean | Ocultar borda superior |
| hideBottom | boolean | Ocultar borda inferior |
| hideLeft | boolean | Ocultar borda esquerda |
| hideRight | boolean | Ocultar borda direita |
| strikethroughHorizontal | boolean | Riscado horizontal da caixa de borda |
| strikethroughVertical | boolean | Riscado vertical da caixa de borda |
| strikethroughBottomLeftToTopRight | boolean | Riscado da caixa de borda de baixo-esquerda para cima-direita |
| strikethroughTopLeftToBottomRight | boolean | Riscado da caixa de borda de cima-esquerda para baixo-direita |

**Retorna:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - novo elemento de caixa de borda