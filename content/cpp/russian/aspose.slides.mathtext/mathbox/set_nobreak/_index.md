---
title: set_NoBreak()
second_title: Справочник API Aspose.Slides для C++
description: "Нет разрыва Это свойство указывает свойство \"unbreakable\" для объектного блока. Когда true, внутри блока не может происходить разрыв строк. Это может быть важно для эмуляторов операторов, состоящих более чем из одного бинарного оператора. Когда этот элемент не указан, внутри блока могут происходить разрывы. По умолчанию: true"
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) метод

No break Это свойство указывает свойство "unbreakable" для объектного блока. Когда true, внутри блока не может происходить разрыв строк. Это может быть важно для эмуляторов операторов, состоящих более чем из одного бинарного оператора. Когда этот элемент не указан, внутри блока могут происходить разрывы. Default: true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## Примечания

Example: 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## См. также

* Класс [MathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)