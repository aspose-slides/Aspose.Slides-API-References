---
title: CreateMathBorderBox()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma caixa de borda matemática aplicando ao elemento
type: docs
weight: 1
url: /pt/aspose.slides.mathtext/mathborderboxfactory/createmathborderbox/
---
## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>) method


Cria uma caixa de borda matemática aplicando ao elemento

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element) override
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar a caixa de borda |

### Return Value

novo elemento de caixa de borda

## MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) method


Cria uma caixa de borda matemática aplicando ao elemento

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathBorderBoxFactory::CreateMathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | elemento matemático ao qual aplicar a caixa de borda |
| hideTop | **bool** | Ocultar borda superior |
| hideBottom | **bool** | Ocultar borda inferior |
| hideLeft | **bool** | Ocultar borda esquerda |
| hideRight | **bool** | Ocultar borda direita |
| strikethroughHorizontal | **bool** | Riscado horizontal da caixa de borda |
| strikethroughVertical | **bool** | Riscado vertical da caixa de borda |
| strikethroughBottomLeftToTopRight | **bool** | Riscado da caixa de borda da parte inferior esquerda para a superior direita |
| strikethroughTopLeftToBottomRight | **bool** | Riscado da caixa de borda da parte superior esquerda para a inferior direita |

### Return Value

novo elemento de caixa de borda

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBorderBoxFactory](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)