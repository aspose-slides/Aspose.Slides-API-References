---
title: set_OperatorEmulator()
second_title: Aspose.Slides для C++ справочник API
description: "Эмулятор оператора. Когда значение true, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. Это значит, например, что символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов комбинируются в оператор, например '=='. Значение по умолчанию: false"
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathbox/set_operatoremulator/
---
## MathBox::set_OperatorEmulator(bool) метод

Эмулятор оператора. Когда значение true, коробка и её содержимое ведут себя как один оператор и наследуют свойства оператора. Это значит, например, что символ может служить точкой разрыва строки и может быть выровнен с другими операторами. Эмуляторы операторов часто используются, когда один или несколько глифов комбинируются в оператор, например '=='. Значение по умолчанию: false

```cpp
void Aspose::Slides::MathText::MathBox::set_OperatorEmulator(bool value) override
```

## Примечания

Пример:
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"=="));
box->set_OperatorEmulator(true);
```

## Смотрите также

* Класс [MathBox](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)