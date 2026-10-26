---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, os delimitadores crescem verticalmente para corresponder à altura do seu operando. O valor padrão é true
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() método

Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, os delimitadores crescem verticalmente para corresponder à altura do seu operando. O valor padrão é true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Observações

Exemplo: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Ver Também

* Classe [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)