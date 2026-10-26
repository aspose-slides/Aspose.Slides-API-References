---
title: set_EndingCharacter()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Znak końcowy ogranicznika określa znak kończący lub zamykający ogranicznik. Ograniczniki matematyczne to znaki otaczające, takie jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: ')'."
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/mathdelimiter/set_endingcharacter/
---

## MathDelimiter::set_EndingCharacter(char16_t) metoda

Znak końcowy ogranicznika określa znak kończący lub zamykający ogranicznik. Ograniczniki matematyczne to znaki otaczające, takie jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: ')'.

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_EndingCharacter(char16_t value) override
```

## Uwagi

Przykład: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Zobacz także

* Klasa [MathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)