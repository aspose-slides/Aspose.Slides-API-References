---
title: set_EndingCharacter()
second_title: Aspose.Slides dla C++ – odniesienie API
description: "Znak końcowy delimitera określa znak zakończenia lub zamknięcia delimitera. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: ')'."
type: docs
weight: 79
url: /pl/aspose.slides.mathtext/imathdelimiter/set_endingcharacter/
---
## IMathDelimiter::set_EndingCharacter(char16_t) metoda


Znak końcowy delimitera określa znak końcowy lub zamykający delimiter. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślnie: ')'.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_EndingCharacter(char16_t value)=0
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