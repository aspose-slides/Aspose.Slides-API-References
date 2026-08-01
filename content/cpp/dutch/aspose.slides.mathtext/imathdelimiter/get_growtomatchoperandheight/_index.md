---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides voor C++ API-referentie
description: Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeien de delimiters verticaal om hun operandhoogte overeen te laten komen. De standaardwaarde is true
type: docs
weight: 92
url: /nl/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() methode

Specificeert de groei van BeginningCharacter, SeparatorCharacter, EndingCharacter. Wanneer true, groeit de delimiter verticaal om de operandhoogte overeen te laten komen. De standaardwaarde is true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## Opmerkingen

Voorbeeld:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## Zie ook

* Klasse [IMathDelimiter](../)
* Naamruimte [Aspose::Slides::MathText](../../)
* Bibliotheek [Aspose.Slides](../../../)