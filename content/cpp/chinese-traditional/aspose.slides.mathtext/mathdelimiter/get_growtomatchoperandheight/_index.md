---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長方式。當 true 時，分隔符會垂直成長以匹配其運算元高度。預設值為 true
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/get_growtomatchoperandheight/
---
## MathDelimiter::get_GrowToMatchOperandHeight() 方法

指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長方式。當 true 時，分隔符會垂直成長以匹配其運算元高度。預設值為 true

```cpp
bool Aspose::Slides::MathText::MathDelimiter::get_GrowToMatchOperandHeight() override
```

## 備註

範例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 另請參閱

* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)