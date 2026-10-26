---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 參考
description: 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增長。當為 true 時，分隔符會垂直成長以匹配其運算元高度。預設值為 true
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/set_growtomatchoperandheight/
---
## MathDelimiter::set_GrowToMatchOperandHeight(bool) 方法

指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增長。當為 true 時，分隔符會垂直成長以匹配其運算元高度。預設值為 true

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_GrowToMatchOperandHeight(bool value) override
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