---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides para C++ Referência da API
description: Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando verdadeiro, os delimitadores crescem verticalmente para corresponder à altura do operando. O valor padrão é true
type: docs
weight: 105
url: /pt/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) método

Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter. Quando verdadeiro, os delimitadores crescem verticalmente para corresponder à altura do operando. O valor padrão é true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## Observações

Exemplo:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Veja Também

* Classe [IMathDelimiter](../)
* Espaço de nomes [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)