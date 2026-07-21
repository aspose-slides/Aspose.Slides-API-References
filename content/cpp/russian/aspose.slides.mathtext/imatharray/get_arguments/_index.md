---
title: get_Arguments()
second_title: Aspose.Slides для справочника API C++
description: Набор элементов массива
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imatharray/get_arguments/
---
## IMathArray::get_Arguments() метод

Набор элементов массива

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathArray::get_Arguments()=0
```

## Примечания

Пример: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->get_Arguments()->Add(System::MakeObject<MathematicalText>(u"item2"));
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElementCollection](../../imathelementcollection/)
* Класс [IMathArray](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)