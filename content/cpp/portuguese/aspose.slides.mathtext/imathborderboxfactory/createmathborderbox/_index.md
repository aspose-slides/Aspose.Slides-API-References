---
title: CreateMathBorderBox()
second_title: Aspose.Slides para C++ Referência da API
description: Crie uma caixa de borda matemática aplicando ao elemento
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/imathborderboxfactory/createmathborderbox/
---
## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) método

Crie uma caixa de borda matemática aplicando ao elemento

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar a caixa de borda |

### Valor de Retorno

novo elemento de caixa de borda

## IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) método

Crie uma caixa de borda matemática aplicando ao elemento

```cpp
virtual System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::IMathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar a caixa de borda |
| hideTop | **bool** | Ocultar borda superior |
| hideBottom | **bool** | Ocultar borda inferior |
| hideLeft | **bool** | Ocultar borda esquerda |
| hideRight | **bool** | Ocultar borda direita |
| strikethroughHorizontal | **bool** | Riscado horizontal da caixa de borda |
| strikethroughVertical | **bool** | Riscado vertical da caixa de borda |
| strikethroughBottomLeftToTopRight | **bool** | Riscado da caixa de borda de canto inferior esquerdo para canto superior direito |
| strikethroughTopLeftToBottomRight | **bool** | Riscado da caixa de borda de canto superior esquerdo para canto inferior direito |

### Valor de Retorno

novo elemento de caixa de borda

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [IMathElement](../../imathelement/)
* Classe [IMathBorderBoxFactory](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)