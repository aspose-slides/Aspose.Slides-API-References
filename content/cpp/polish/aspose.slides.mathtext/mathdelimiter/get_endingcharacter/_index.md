---
title: get_EndingCharacter()
second_title: Odwołanie API Aspose.Slides dla C++
description: "Znak końcowy delimitera określa końcowy, czyli zamykający, znak delimitera. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: ')'."
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() metoda


Znak końcowy delimitera określa końcowy, czyli zamykający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Uwagi


Przykład:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Zobacz również

* Klasa [MathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)