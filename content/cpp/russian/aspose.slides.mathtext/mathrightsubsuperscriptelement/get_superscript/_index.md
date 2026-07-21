---
title: get_Superscript()
second_title: Справка API Aspose.Slides для C++
description: Аргумент верхнего индекса
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_superscript/
---
## MathRightSubSuperscriptElement::get_Superscript() метод

Аргумент верхнего индекса

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_Superscript() override
```

## Примечания


Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = subsuperscript->get_Superscript();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathRightSubSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)