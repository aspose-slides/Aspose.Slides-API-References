---
title: set_BeginningCharacter()
second_title: Aspose.Slides for C++ API Reference
description: "Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: '('."
type: docs
weight: 27
url: /cpp/aspose.slides.mathtext/imathdelimiter/set_beginningcharacter/
---
## IMathDelimiter::set_BeginningCharacter(char16_t) method


Delimiter Beginning Character specifies the beginning, or opening, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default value: '('.

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_BeginningCharacter(char16_t value)=0
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