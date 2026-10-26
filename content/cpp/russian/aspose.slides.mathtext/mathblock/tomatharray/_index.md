---
title: ToMathArray()
second_title: Aspose.Slides для C++ справочник API
description: Размещает дочерние элементы в вертикальном массиве
type: docs
weight: 235
url: /ru/aspose.slides.mathtext/mathblock/tomatharray/
---
## MathBlock::ToMathArray() метод

Помещает дочерние элементы в вертикальный массив

```cpp
System::SharedPtr<IMathArray> Aspose::Slides::MathText::MathBlock::ToMathArray() override
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
* Класс [MathBlock](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)