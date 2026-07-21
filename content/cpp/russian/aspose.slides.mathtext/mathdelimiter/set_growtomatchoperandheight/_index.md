---
title: set_GrowToMatchOperandHeight()
second_title: Справочник API Aspose.Slides для C++
description: Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true
type: docs
weight: 105
url: /ru/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) метод

Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда значение true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## Примечания

Пример:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## См. также

* Класс [MathDelimiter](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)