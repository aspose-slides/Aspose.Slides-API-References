---
title: get_StrikethroughBottomLeftToTopRight()
second_title: Referência da API Aspose.Slides para C++
description: Riscar da parte inferior esquerda para a superior direita (padrão é false). Especifica o estado oculto ou visível de uma linha diagonal de riscado do canto inferior esquerdo ao canto superior direito da caixa de borda.
type: docs
weight: 170
url: /pt/aspose.slides.mathtext/imathborderbox/get_strikethroughbottomlefttotopright/
---
## IMathBorderBox::get_StrikethroughBottomLeftToTopRight() método


Riscar da parte inferior esquerda para a superior direita (o padrão é false). Especifica o estado oculto ou exibido de uma linha diagonal de riscado do canto inferior esquerdo ao canto superior direito da caixa de borda.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_StrikethroughBottomLeftToTopRight()=0
```

## Observações


Exemplo:
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_StrikethroughBottomLeftToTopRight(true);
```

## Ver também

* Classe [IMathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)