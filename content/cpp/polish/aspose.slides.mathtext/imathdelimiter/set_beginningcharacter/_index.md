---
title: set_BeginningCharacter()
second_title: Aspose.Slides dla C++ - odniesienie API
description: "Delimiter Beginning Character określa początkowy, czyli otwierający znak delimitera. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślna wartość: '('."
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) metoda

Delimiter Beginning Character określa początkowy, czyli otwierający znak delimitera. Matematyczne delimitery są znakami otaczającymi, takimi jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślna wartość: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
```

## Uwagi

Przykład:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Zobacz także

* Klasa [IMathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)