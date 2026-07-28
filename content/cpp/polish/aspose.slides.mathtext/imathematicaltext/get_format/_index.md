---
title: get_Format()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Właściwości formatowania tekstu
type: docs
weight: 27
url: /pl/aspose.slides.mathtext/imathematicaltext/get_format/
---
## IMathematicalText::get_Format() metoda

Właściwości formatowania tekstu

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::MathText::IMathematicalText::get_Format()=0
```

## Uwagi

Przykład:
```cpp
auto mathText = System::MakeObject<MathematicalText>(u"x+y");
mathText->get_Format()->set_FontHeight(28.0f);
```

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IPortionFormat](../../../aspose.slides/iportionformat/)
* Klasa [IMathematicalText](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)