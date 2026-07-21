---
title: get_Superscript()
second_title: Aspose.Slides для C++ справочник API
description: Аргумент верхнего индекса
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_superscript/
---
## IMathRightSubSuperscriptElement::get_Superscript() метод


Аргумент верхнего индекса

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_Superscript()=0
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

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathRightSubSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)