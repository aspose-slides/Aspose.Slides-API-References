---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 参考
description: 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长方式。当值为 true 时，分隔符会垂直增长以匹配其操作数高度。默认值为 true
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() 方法


指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长方式。当 true 时，分隔符会垂直增长以匹配其操作数高度。默认值为 true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## 备注


示例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 另请参阅

* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)