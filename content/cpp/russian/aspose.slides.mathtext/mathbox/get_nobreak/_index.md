---
title: get_NoBreak()
second_title: Справочник API Aspose.Slides для C++
description: "Без разрыва Это свойство указывает свойство \"unbreakable\" у объекта коробки. При true разрывы строк не могут происходить внутри коробки. Это может быть важно для эмуляторов операторов, состоящих из более чем одного бинарного оператора. Если этот элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true"
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() метод


Без разрыва Это свойство указывает свойство \"неразрывный\" у объекта коробки. При true разрывы строк не могут происходить внутри коробки. Это может быть важно для эмуляторов операторов, состоящих более чем из одного бинарного оператора. Когда этот элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## Примечания


Пример:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## См. также

* Класс [MathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)