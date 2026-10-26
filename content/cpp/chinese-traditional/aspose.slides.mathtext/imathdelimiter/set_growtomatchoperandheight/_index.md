---
title: set_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 參考
description: 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長方式。當為 true 時，分隔符會垂直增長以匹配其運算元高度。預設值為 true
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/set_growtomatchoperandheight/
---
## IMathDelimiter::set_GrowToMatchOperandHeight(bool) 方法


指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的成長方式。當為 true 時，分隔符會垂直增長以匹配其運算元高度。預設值為 true

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_GrowToMatchOperandHeight(bool value)=0
```

## 備註


範例: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 另請參閱

* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)