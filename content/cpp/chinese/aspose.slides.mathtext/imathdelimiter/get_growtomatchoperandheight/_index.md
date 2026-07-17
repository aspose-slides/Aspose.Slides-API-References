---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides C++ API 参考
description: 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长方式。当为 true 时，分隔符在垂直方向上增长以匹配其操作数的高度。默认值为 true
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() 方法

指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增长方式。当为 true 时，分隔符在垂直方向上增长以匹配其操作数的高度。默认值为 true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## 备注

示例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 另请参见

* 类 [IMathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)