---
title: get_NoBreak()
second_title: Aspose.Slides для C++ справочник API
description: "Без разрыва. Это свойство указывает свойство \"unbreakable\" у коробки объекта. Если значение true, внутри коробки не может происходить разрыв строк. Это может быть важно для эмуляторов операторов, состоящих более чем из одного двоичного оператора. Если этот элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true"
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() метод


Без разрыва. Это свойство указывает свойство \"unbreakable\" у коробки объекта. Если значение true, внутри коробки не может происходить разрыв строк. Это может быть важно для эмуляторов операторов, состоящих более чем из одного двоичного оператора. Если этот элемент не указан, разрывы могут происходить внутри коробки. По умолчанию: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## Примечания


Пример: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## См. также

* Класс [IMathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)