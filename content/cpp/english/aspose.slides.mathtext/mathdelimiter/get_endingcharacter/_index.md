---
title: get_EndingCharacter()
second_title: Aspose.Slides for C++ API Reference
description: "Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'."
type: docs
weight: 66
url: /aspose.slides.mathtext/mathdelimiter/get_endingcharacter/
---
## MathDelimiter::get_EndingCharacter() method


Delimiter Ending Character specifies the ending, or closing, delimiter character. Mathematical delimiters are enclosing characters such as parentheses, brackets, and braces. The default: ')'.

```cpp
char16_t Aspose::Slides::MathText::MathDelimiter::get_EndingCharacter() override
```

## Remarks


Example: 
```cpp
auto delimiter = System::ExplicitCast<IMathElement>(System::MakeObject<MathematicalText>(u"x")->Join(u"y"))->Enclose();
delimiter->set_EndingCharacter(u']');
```

## See Also

* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)