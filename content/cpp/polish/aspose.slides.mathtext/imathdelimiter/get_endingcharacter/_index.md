---
title: get_EndingCharacter()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Delimiter Ending Character określa znak końcowy, czyli zamykający, delimiter. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: ')'."
type: docs
weight: 66
url: /pl/aspose.slides.mathtext/imathdelimiter/get_endingcharacter/
---
## IMathDelimiter::get_EndingCharacter() metoda


Delimiter Ending Character określa znak końcowy, czyli zamykający, delimiter. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: ')'.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_EndingCharacter()=0
```

## Uwagi


Przykład: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## Zobacz także

* Klasa [IMathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)