---
title: get_NoBreak()
second_title: Aspose.Slides for C++ API 參考
description: "不換行。此屬性指定物件盒的 \"unbreakable\" 屬性。當為 true 時，盒內不會出現換行。對於包含多個二元運算子的運算子模擬器而言，這可能非常重要。若未指定此元素，盒內可能會出現換行。預設值： true"
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/imathbox/get_nobreak/
---
## IMathBox::get_NoBreak() 方法


不換行。此屬性指定物件盒的 \"unbreakable\" 屬性。當 true 時，盒內不得出現換行。對於包含多個二元運算子的運算子模擬器而言，這可能很重要。若未指定此元素，盒內可能會出現換行。Default: true

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_NoBreak()=0
```

## 備註


範例: 
```cpp
auto box = System::MakeObject<MathematicalText>(u"**********")->ToBox();
box->set_NoBreak(false);
```

## 另請參閱

* 類別 [IMathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)