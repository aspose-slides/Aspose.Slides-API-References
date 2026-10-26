---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API 参考
description: 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长方式。当为 true 时，定界符会垂直增长以匹配其操作数的高度。默认值为 true
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) 方法

指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长方式。当为 true 时，定界符会垂直增长以匹配其操作数的高度。默认值为 true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
```

## 备注


示例: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 另见

* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)