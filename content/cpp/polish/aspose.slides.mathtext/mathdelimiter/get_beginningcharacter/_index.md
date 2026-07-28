---
title: get_BeginningCharacter()
second_title: Aspose.Slides dla C++ Dokumentacja API
description: "Delimiter Beginning Character określa początkowy, czyli otwierający, znak ogranicznika. Matematyczne ograniczniki to znaki otaczające, takie jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślny: '('."
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/mathdelimiter/get_beginningcharacter/
---
## MathDelimiter::get_BeginningCharacter() metoda

Delimiter Beginning Character określa początkowy, czyli otwierający, znak ogranicznika. Matematyczne ograniczniki to znaki otaczające, takie jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślne: '('.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_BeginningCharacter() override
```

## Uwagi

Przykład: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Zobacz także

* Klasa [MathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)