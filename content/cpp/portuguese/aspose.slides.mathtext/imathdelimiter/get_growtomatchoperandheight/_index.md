---
title: get_GrowToMatchOperandHeight()
second_title: Referência da API Aspose.Slides para C++
description: Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, os delimitadores crescem verticalmente para corresponder à altura do seu operando. O valor padrão é true
type: docs
weight: 92
url: /pt/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() método

Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando true, os delimitadores crescem verticalmente para corresponder à altura do seu operando. O valor padrão é true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Observações

Exemplo:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Veja Também

* Classe [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Biblioteca [Aspose.Slides](../../../)