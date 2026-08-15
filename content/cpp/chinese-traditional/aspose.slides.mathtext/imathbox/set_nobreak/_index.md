---
title: set_NoBreak()
second_title: Aspose.Slides for C++ API 參考
description: "無換行。此屬性指定物件盒的 \"unbreakable\" 屬性。當為 true 時，盒子內部不會出現換行。這對於包含多個二元運算子的運算子模擬器可能很重要。若未指定此元素，盒子內部可能會發生換行。預設值: true"
type: docs
weight: 53
url: /zh-hant/aspose.slides.mathtext/imathbox/set_nobreak/
---
## IMathBox::set_NoBreak(bool) 方法

無換行。此屬性指定物件框的「unbreakable」屬性。當為 true 時，盒子內部不會出現換行。這對於由多個二元運算子組成的運算子模擬器很重要。如果未指定此元素，盒子內部可能會出現換行。預設值: true

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_NoBreak(bool value)=0
```

## 備註


範例:
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## 參見

* 類別 [IMathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)