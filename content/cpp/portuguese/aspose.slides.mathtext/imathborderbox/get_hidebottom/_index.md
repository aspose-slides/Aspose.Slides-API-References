---
title: get_HideBottom()
second_title: Referência da API Aspose.Slides para C++
description: Ocultar a borda inferior (padrão é false) - especifica o estado oculto ou visível da borda inferior da caixa de borda.
type: docs
weight: 40
url: /pt/aspose.slides.mathtext/imathborderbox/get_hidebottom/
---
## IMathBorderBox::get_HideBottom() método

Ocultar a borda inferior (padrão é false) - especifica se a borda inferior da caixa de borda está oculta ou visível.

```cpp
virtual bool Aspose::Slides::MathText::IMathBorderBox::get_HideBottom()=0
```

## Observações

Exemplo: 
```cpp
auto borderBox = System::MakeObject<MathematicalText>(u"x+y+z")->ToBorderBox();
borderBox->set_HideBottom(true);
```

## Veja também

* Classe [IMathBorderBox](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)