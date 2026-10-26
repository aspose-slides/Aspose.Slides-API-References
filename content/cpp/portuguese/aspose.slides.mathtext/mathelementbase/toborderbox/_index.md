---
title: ToBorderBox()
second_title: Aspose.Slides para C++ Referência da API
description: Posiciona este elemento em uma caixa de borda
type: docs
weight: 248
url: /pt/aspose.slides.mathtext/mathelementbase/toborderbox/
---
## MathElementBase::ToBorderBox() método

Posiciona este elemento em uma caixa de borda

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox() override
```

### Valor de Retorno

Caixa de borda com este elemento posicionado dentro

## Observações



Exemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
```

## MathElementBase::ToBorderBox(bool, bool, bool, bool, bool, bool, bool, bool) método

Posiciona este elemento em uma caixa de borda

```cpp
System::SharedPtr<IMathBorderBox> Aspose::Slides::MathText::MathElementBase::ToBorderBox(bool hideTop, bool hideBottom, bool hideLeft, bool hideRight, bool strikethroughHorizontal, bool strikethroughVertical, bool strikethroughBottomLeftToTopRight, bool strikethroughTopLeftToBottomRight) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| hideTop | **bool** | Ocultar Borda Superior |
| hideBottom | **bool** | Ocultar Borda Inferior |
| hideLeft | **bool** | Ocultar Borda Esquerda |
| hideRight | **bool** | Ocultar Borda Direita |
| strikethroughHorizontal | **bool** | Tachado Horizontal da Caixa de Borda |
| strikethroughVertical | **bool** | Tachado Vertical da Caixa de Borda |
| strikethroughBottomLeftToTopRight | **bool** | Tachado da Caixa de Borda da Inferior-Esquerda para a Superior-Direita |
| strikethroughTopLeftToBottomRight | **bool** | Tachado da Caixa de Borda da Superior-Esquerda para a Inferior-Direita |

### Valor de Retorno

Caixa de borda com este elemento posicionado dentro

## Observações



Exemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox(false, false, true, true, false, false, false, false);
```

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMathBorderBox](../../imathborderbox/)
* Classe [MathElementBase](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)