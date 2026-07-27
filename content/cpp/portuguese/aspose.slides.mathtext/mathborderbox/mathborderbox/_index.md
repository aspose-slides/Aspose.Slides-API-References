---
title: MathBorderBox()
second_title: Referência da API Aspose.Slides para C++
description: Cria o elemento MathBorderBox com borda retangular
type: docs
weight: 222
url: /pt/aspose.slides.mathtext/mathborderbox/mathborderbox/
---
## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>) construtor

Cria o elemento [MathBorderBox](../) com borda retangular

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento base ao qual a caixa de borda é aplicada. Pode ser nulo. |

## Observações

Exemplo:
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"));
```

## MathBorderBox::MathBorderBox(System::SharedPtr\<IMathElement\>, bool, bool, bool, bool, bool, bool, bool, bool) construtor

Cria o elemento [MathBorderBox](../)

```cpp
Aspose::Slides::MathText::MathBorderBox::MathBorderBox(System::SharedPtr<IMathElement> element, bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight)
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| element | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> | O elemento base ao qual a caixa de borda é aplicada |
| hideTop | **bool** | Ocultar borda superior |
| hideBottom | **bool** | Ocultar borda inferior |
| hideLeft | **bool** | Ocultar borda esquerda |
| hideRight | **bool** | Ocultar borda direita |
| strikethroughHorizontal | **bool** | Riscado horizontal |
| strikethroughVertical | **bool** | Riscado vertical |
| strikethroughBottomLeftToTopRight | **bool** | Riscado de canto inferior esquerdo para canto superior direito |
| strikethroughTopLeftToBottomRight | **bool** | Riscado de canto superior esquerdo para canto inferior direito |

## Observações

Exemplo:
```cpp
auto borderBox = System::MakeObject<MathBorderBox>(System::MakeObject<MathematicalText>(u"x"), true, true, true, false, true, true, true, true);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathElement](../../imathelement/)
* Classe [MathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)