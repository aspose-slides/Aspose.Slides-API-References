---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides для справки API C++
description: Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда значение true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() метод


Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда значение true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Замечания


Пример: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## См. также

* Класс [MathDelimiter](../)
* Пространство имен [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)