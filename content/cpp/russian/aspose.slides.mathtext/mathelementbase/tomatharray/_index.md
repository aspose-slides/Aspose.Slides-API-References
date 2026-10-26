---
title: ToMathArray()
second_title: Справочник API Aspose.Slides для C++
description: Размещает в вертикальном массиве
type: docs
weight: 170
url: /ru/aspose.slides.mathtext/mathelementbase/tomatharray/
---
## MathElementBase::ToMathArray() метод


Размещает в вертикальном массиве

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathElementBase::ToMathArray() override
```


### Возвращаемое значение

Новый экземпляр типа [IMathArray](../../imatharray/)
## Примечания



Пример: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## См. также

* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [IMathArray](../../imatharray/)
* Класс [MathElementBase](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)