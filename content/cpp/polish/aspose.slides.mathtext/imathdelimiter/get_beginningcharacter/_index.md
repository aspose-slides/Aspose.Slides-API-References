---
title: get_BeginningCharacter()
second_title: Aspose.Slides dla C++ - referencja API
description: "Delimiter Beginning Character określa początkowy, czyli otwierający znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślna wartość: '('."
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() metoda


Delimiter Beginning Character określa początkowy, czyli otwierający, znak delimitera. Matematyczne delimitery to znaki otaczające, takie jak nawiasy okrągłe, kwadratowe i klamrowe. Domyślna wartość: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Uwagi


Przykład: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## Zobacz też

* Klasa [IMathDelimiter](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)