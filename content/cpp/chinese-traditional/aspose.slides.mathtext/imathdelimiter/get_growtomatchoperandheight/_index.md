---
title: get_GrowToMatchOperandHeight()
second_title: Aspose.Slides for C++ API 參考文件
description: 指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增長。當為 true 時，分隔符會垂直增長以匹配其運算元高度。預設值為 true
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/get_growtomatchoperandheight/
---
## IMathDelimiter::get_GrowToMatchOperandHeight() method


指定 BeginningCharacter、SeparatorCharacter、EndingCharacter 的增長。當為 true 時，分隔符會垂直增長以匹配其運算元高度。預設值為 true

```cpp
virtual bool Aspose::Slides::MathText::IMathDelimiter::get_GrowToMatchOperandHeight()=0
```

## 備註


範例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_GrowToMatchOperandHeight(false);
```

## 參見

* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)