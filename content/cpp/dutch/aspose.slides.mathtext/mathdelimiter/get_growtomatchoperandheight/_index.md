---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeit de delimiter verticaal om de hoogte van zijn operand te evenaren. De standaardwaarde is true
type: docs
weight: 92
url: /nl/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() methode

Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer waar, groeit de delimiter verticaal om de hoogte van zijn operand te evenaren. De standaardwaarde is waar

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Opmerkingen

Voorbeeld:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Zie ook

* Klasse [MathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)