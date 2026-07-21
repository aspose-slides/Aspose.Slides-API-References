---
title: get_Superscript()
second_title: Aspose.Slides для C++ справочник API
description: Указывает аргумент надстрочного индекса, который, например, в случае интеграла, задаёт верхний предел
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathnaryoperator/get_superscript/
---
## MathNaryOperator::get_Superscript() метод


Указывает аргумент надстрочного индекса, который, например, в случае интеграла, задаёт верхний предел

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Superscript() override
```

## Примечания


Пример: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto superscriptArg = naryOperator->get_Superscript();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElement](../../imathelement/)
* Класс [MathNaryOperator](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)