---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API 參考
description: "不換行 此屬性指定物件框的 \"unbreakable\" 屬性。當為 true 時，框內不得換行。這對於包含多個二元運算子的運算子模擬器可能很重要。若未指定此元素，框內可換行。預設值： true"
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/mathbox/set_nobreak/
---
## MathBox::set_NoBreak(bool) 方法

不換行 此屬性指定物件框的「unbreakable」屬性。當為 true 時，框內不得換行。這對於包含多個二元運算子的運算子模擬器可能很重要。若未指定此元素，框內可換行。預設值： true

```cpp
void Aspose::Slides::MathText::MathBox::set_NoBreak(bool value) override
```

## 備註

範例：
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## 另見

* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)