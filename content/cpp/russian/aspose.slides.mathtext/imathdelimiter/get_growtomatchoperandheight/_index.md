---
title: get_GrowToMatchOperandHeight()
second_title: Справка API Aspose.Slides для C++
description: Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true
type: docs
weight: 92
url: /ru/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() метод


Указывает рост BeginningCharacter, SeparatorCharacter, EndingCharacter. Когда true, разделители растут вертикально, чтобы соответствовать высоте их операнда. Значение по умолчанию — true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
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