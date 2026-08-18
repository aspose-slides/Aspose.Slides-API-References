---
title: IMathBorderBoxFactory
second_title: Aspose.Slides for Java Referência da API
description: Permite criar uma caixa de borda matemática
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
| [createMathBorderBox(IMathElement element)](#createMathBorderBox-com.aspose.slides.IMathElement-) | Criar uma caixa de borda matemática aplicando ao elemento |
| [createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)](#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-) | Criar uma caixa de borda matemática aplicando ao elemento |
### createMathBorderBox(IMathElement element) {#createMathBorderBox-com.aspose.slides.IMathElement-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element)
```

Criar uma caixa de borda matemática aplicando ao elemento

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático para aplicar a caixa de borda |

**Retorno:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - novo elemento de caixa de borda
### createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight) {#createMathBorderBox-com.aspose.slides.IMathElement-boolean-boolean-boolean-boolean-boolean-boolean-boolean-boolean-}
```
public abstract IMathBorderBox createMathBorderBox(IMathElement element, boolean hideTop, boolean hideBottom, boolean hideLeft, boolean hideRight, boolean strikethroughHorizontal, boolean strikethroughVertical, boolean strikethroughBottomLeftToTopRight, boolean strikethroughTopLeftToBottomRight)
```

Criar uma caixa de borda matemática aplicando ao elemento

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [IMathElement](../../com.aspose.slides/imathelement) | elemento matemático para aplicar a caixa de borda |
| hideTop | boolean | Ocultar borda superior |
| hideBottom | boolean | Ocultar borda inferior |
| hideLeft | boolean | Ocultar borda esquerda |
| hideRight | boolean | Ocultar borda direita |
| strikethroughHorizontal | boolean | Traçado horizontal da caixa de borda |
| strikethroughVertical | boolean | Traçado vertical da caixa de borda |
| strikethroughBottomLeftToTopRight | boolean | Traçado da caixa de borda de canto inferior esquerdo para superior direito |
| strikethroughTopLeftToBottomRight | boolean | Traçado da caixa de borda de canto superior esquerdo para inferior direito |

**Retorno:**
[IMathBorderBox](../../com.aspose.slides/imathborderbox) - novo elemento de caixa de borda