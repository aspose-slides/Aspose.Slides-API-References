---
title: set_GrowToMatchOperandHeight()
second_title: Referência da API Aspose.Slides para C++
description: Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter Quando true, os delimitadores crescem verticalmente para corresponder à altura do operando. O valor padrão é true
type: docs
weight: 105
url: /pt/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) método


Especifica o crescimento de BeginningCharacter, SeparatorCharacter, EndingCharacter Quando verdadeiro, os delimitadores crescem verticalmente para corresponder à altura do operando. O valor padrão é verdadeiro

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## Observações


Exemplo: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Ver Também

* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)