---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API Reference
description: Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true
type: docs
weight: 92
url: /aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() method


Specifies the growth of BeginningCharacter, SeparatorCharacter, EndingCharacter When true, the delimiters grows vertically to match its operand height. The default value is true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## Remarks


Example: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## See Also

* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)