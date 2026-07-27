---
title: set_BaseJustification()
second_title: Referência da API Aspose.Slides para C++
description: "Especifica o alinhamento da matriz em relação ao texto ao redor. Texto fora da matriz pode ser alinhado com a parte inferior, superior ou central de um objeto de matriz. Valor padrão: Center"
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/imatharray/set_basejustification/
---
## IMathArray::set_BaseJustification(MathVerticalAlignment) método

Especifica o alinhamento da matriz em relação ao texto ao redor. O texto fora da matriz pode ser alinhado com a parte inferior, superior ou central de um objeto de matriz. Valor padrão: Center

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_BaseJustification(MathVerticalAlignment value)=0
```

## Observações

Exemplo: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_BaseJustification(MathVerticalAlignment::Top);
```

## Ver também

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Classe [IMathArray](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)