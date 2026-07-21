---
title: get_Subscript()
second_title: Aspose.Slides для C++ справочник API
description: Аргумент нижнего индекса
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_subscript/
---
## MathRightSubSuperscriptElement::get_Subscript() метод

Аргумент нижнего индекса

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Subscript() override
```

## Примечания

Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sub = subsuperscript->get_Subscript();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)