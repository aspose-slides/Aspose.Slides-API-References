---
title: get_BeginningCharacter()
second_title: Aspose.Slides for C++ API Reference
description: "Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: '('."
type: docs
weight: 14
url: /aspose.slides.mathtext/imathdelimiter/get_beginningcharacter/
---
## IMathDelimiter::get_BeginningCharacter() method


Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: '('.

```cpp
virtual char16_t Aspose::Slides::MathText::IMathDelimiter::get_BeginningCharacter()=0
```

## Remarks


Example: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_BeginningCharacter(u'[');
```

## See Also

* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)