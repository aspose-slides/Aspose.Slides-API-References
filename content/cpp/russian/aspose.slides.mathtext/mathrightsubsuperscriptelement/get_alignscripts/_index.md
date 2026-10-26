---
title: get_AlignScripts()
second_title: Aspose.Slides для C++ API справочник
description: Указывает выравнивание подстрочного/надстрочного индекса. Когда true, подстрочный и надстрочный индексы выравниваются горизонтально относительно друг друга. Когда false, они кёрнятся к форме основы. Значение по умолчанию — false.
type: docs
weight: 27
url: /ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/get_alignscripts/
---
## MathRightSubSuperscriptElement::get_AlignScripts() метод


Указывает выравнивание подстрочного/надстрочного индекса. Когда true, подстрочный и надстрочный индексы выравниваются горизонтально относительно друг друга. Когда false, они кёрнятся к форме основы. Значение по умолчанию — false.

```cpp
bool Aspose::Slides::MathText::MathRightSubSuperscriptElement::get_AlignScripts() override
```

## Примечания


Пример: 
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## Смотрите также

* Класс [MathRightSubSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)