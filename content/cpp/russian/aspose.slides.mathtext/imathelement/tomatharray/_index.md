---
title: ToMathArray()
second_title: Aspose.Slides для C++ справочник API
description: Помещает в вертикальный массив
type: docs
weight: 183
url: /ru/aspose.slides.mathtext/imathelement/tomatharray/
---
## IMathElement::ToMathArray() метод

Помещает в вертикальный массив

```cpp
virtual System::SharedPtr<IMathArray> Aspose::Slides::MathText::IMathElement::ToMathArray()=0
```

### Возвращаемое значение

Новый экземпляр типа [IMathArray](../../imatharray/)
## Замечания



Пример: 
```cpp
auto array = System::MakeObject<MathematicalText>(u"x1")->Join(u"x2")->Join(u"x3")->ToMathArray();
```

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IMathArray](../../imatharray/)
* Класс [IMathElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)