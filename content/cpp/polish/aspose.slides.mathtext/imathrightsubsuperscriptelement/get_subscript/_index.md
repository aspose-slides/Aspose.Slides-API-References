---
title: get_Subscript()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Argument indeksu dolnego
type: docs
weight: 14
url: /pl/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_subscript/
---
## IMathRightSubSuperscriptElement::get_Subscript() metoda


Argument indeksu dolnego

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Subscript()=0
```

## Uwagi


Przykład: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = subsuperscript->get_Subscript();
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IMathElement](../../imathelement/)
* Klasa [IMathRightSubSuperscriptElement](../)
* Przestrzeń nazw [Aspose::Slides::MathText](../../)
* Biblioteka [Aspose.Slides](../../../)