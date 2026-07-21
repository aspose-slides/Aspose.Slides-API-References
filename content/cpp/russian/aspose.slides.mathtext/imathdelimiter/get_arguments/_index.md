---
title: get_Arguments()
second_title: Справочник API Aspose.Slides для C++
description: Один или несколько математических элементов, разделённых символами-делимитерами
type: docs
weight: 1
url: /ru/aspose.slides.mathtext/imathdelimiter/get_arguments/
---
## IMathDelimiter::get_Arguments() метод

Один или несколько математических элементов, разделённых символами-делимитерами

```cpp
virtual System::SharedPtr<IMathElementCollection> Aspose::Slides::MathText::IMathDelimiter::get_Arguments()=0
```

## Примечания

Пример:
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
auto arguments = delimiter->get_Arguments();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathElementCollection](../../imathelementcollection/)
* Класс [IMathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)