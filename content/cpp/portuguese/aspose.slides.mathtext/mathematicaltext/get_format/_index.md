---
title: get_Format()
second_title: Referência da API Aspose.Slides para C++
description: Propriedades de formatação de texto
type: docs
weight: 27
url: /pt/aspose.slides.mathtext/mathematicaltext/get_format/
---
## MathematicalText::get_Format() método

Propriedades de formatação de texto

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::MathematicalText::get_Format() override
```

## Observações

Exemplo: 
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormat](../../../aspose.slides/iportionformat/)
* Classe [MathematicalText](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)