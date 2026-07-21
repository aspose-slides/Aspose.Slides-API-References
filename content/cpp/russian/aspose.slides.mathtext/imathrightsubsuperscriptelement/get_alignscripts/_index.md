---
title: get_AlignScripts()
second_title: Справочник API Aspose.Slides для C++
description: Указывает выравнивание подстрочного/надстрочного индексов. Если значение true, подстрочный и надстрочный индексы выравниваются горизонтально относительно друг друга. Если значение false, они подгоняются к форме базового символа. Значение по умолчанию — false.
type: docs
weight: 40
url: /ru/aspose.slides.mathtext/imathrightsubsuperscriptelement/get_alignscripts/
---
## IMathRightSubSuperscriptElement::get_AlignScripts() метод


Указывает выравнивание подстрочного/надстрочного индексов. Если значение true, подстрочный и надстрочный индексы выравниваются горизонтально относительно друг друга. Если значение false, они подгоняются к форме базового символа. Значение по умолчанию — false.

```cpp
virtual bool Aspose::Slides::MathText::IMathRightSubSuperscriptElement::get_AlignScripts()=0
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

## См. также

* Class [IMathRightSubSuperscriptElement](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)