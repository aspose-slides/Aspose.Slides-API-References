---
title: get_Superscript()
second_title: Aspose.Slides для C++ справочник API
description: Верхний индекс
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/imathleftsubsuperscriptelement/get_superscript/
---
## IMathLeftSubSuperscriptElement::get_Superscript() method


Верхний индекс

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathLeftSubSuperscriptElement::get_Superscript()=0
```

## Примечания


Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto leftSubSuperscript = System::MakeObject<MathLeftSubSuperscriptElement>(baseElement, subscript, superscript);
auto sup = leftSubSuperscript->get_Superscript();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [IMathLeftSubSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)