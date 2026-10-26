---
title: get_Arguments()
second_title: Справочник API Aspose.Slides для C++
description: Набор элементов массива
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/matharray/get_arguments/
---
## MathArray::get_Arguments() метод


Набор элементов массива

```cpp
System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::MathArray::get_Arguments() override
```

## Примечания


Пример: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElementCollection](../../imathelementcollection/)
* Класс [MathArray](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)