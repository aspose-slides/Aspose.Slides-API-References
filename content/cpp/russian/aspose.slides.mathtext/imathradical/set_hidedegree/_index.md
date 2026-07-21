---
title: set_HideDegree()
second_title: Aspose.Slides для C++ справочник API
description: Скрывать степень. Когда значение true, степень не отображается, как в \\u221A\\uD835\\uDC65
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathradical/set_hidedegree/
---
## IMathRadical::set_HideDegree(bool) метод

Скрывать степень. Если true, степень не отображается, как в \\u221A\\uD835\\uDC65

```cpp
virtual void Aspose::Slides::MathText::IMathRadical::set_HideDegree(bool value)=0
```

## Примечания

Пример:
```cpp
auto radical = System::MakeObject<MathematicalText>(u"x")->Radical(u"3"); // кубический корень
radical->set_HideDegree(true);
```

## См. также

* Класс [IMathRadical](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)