---
title: set_AlignScripts()
second_title: Справочник API Aspose.Slides для C++
description: Указывает выравнивание нижнего и верхнего индексов. Когда значение true, нижний и верхний индексы выравниваются горизонтально друг относительно друга. Когда значение false, они подгоняются к форме базового символа. Значение по умолчанию — false.
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/mathrightsubsuperscriptelement/set_alignscripts/
---
## MathRightSubSuperscriptElement::set_AlignScripts(bool) метод

Указывает выравнивание нижнего и верхнего индексов. Когда значение true, нижний и верхний индексы выравниваются горизонтально друг относительно друга. Когда значение false, они подгоняются к форме базового символа. Значение по умолчанию — false.

```cpp
void Aspose::Slides::MathText::MathRightSubSuperscriptElement::set_AlignScripts(bool value) override
```

## Замечания

Пример:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto superscript = System::MakeObject<MathematicalText>(u"j");
auto subsuperscript = System::MakeObject<MathRightSubSuperscriptElement>(baseElement, subscript, superscript);
subsuperscript->set_AlignScripts(true);
```

## См. также

* Класс [MathRightSubSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)