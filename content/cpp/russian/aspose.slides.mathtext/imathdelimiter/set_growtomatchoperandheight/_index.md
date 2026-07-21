---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides для C++ API Справка
description: Определяет рост BeginningCharacter, SeparatorCharacter, EndingCharacter. При значении true разделители растут вертикально, чтобы соответствовать высоте своего операнда. Значение по умолчанию — true
type: docs
weight: 105
url: /ru/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) метод

Определяет рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда значение true, разделители растут вертикально, чтобы соответствовать высоте своего операнда. Значение по умолчанию — true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## Примечания

Пример:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## См. также

* Класс [IMathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)