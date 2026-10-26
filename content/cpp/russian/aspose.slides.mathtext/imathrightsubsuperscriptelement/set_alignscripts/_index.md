---
title: set_AlignScripts()
second_title: Aspose.Slides для C++ API Справочник
description: Указывает выравнивание нижних/верхних индексов. Когда true, нижний и верхний индексы выравниваются горизонтально друг относительно друга. Когда false, они подгоняются к форме базового символа. Значение по умолчанию — false.
type: docs
weight: 53
url: /ru/aspose.slides.mathtext/imathrightsubsuperscriptelement/set_alignscripts/
---
## IMathRightSubSuperscriptElement::set_AlignScripts(bool) метод

Указывает выравнивание нижних/верхних индексов. Когда true, нижний и верхний индексы выравниваются горизонтально друг относительно друга. Когда false, они подгоняются к форме базового символа. Значение по умолчанию — false.

```cpp
virtual void Aspose::Slides::MathText::IMathRightSubSuperscriptElement::set_AlignScripts(bool value)=0
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

* Класс [IMathRightSubSuperscriptElement](../)
* Пространство имён [Aspose::Slides::MathText](../../)
* Библиотека [Aspose.Slides](../../../)