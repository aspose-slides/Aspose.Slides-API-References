---
title: get_Subscript()
second_title: Aspose.Slides для C++: справочник API
description: Задает аргумент индекса, который, например, в случае интеграла, устанавливает нижний предел
type: docs
weight: 14
url: /ru/aspose.slides.mathtext/mathnaryoperator/get_subscript/
---
## MathNaryOperator::get_Subscript() метод


Задаёт аргумент индекса, который, например, в случае интеграла, устанавливает нижний предел

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathNaryOperator::get_Subscript() override
```

## Примечания


Пример: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
auto subscriptArg = naryOperator->get_Subscript();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathNaryOperator](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)