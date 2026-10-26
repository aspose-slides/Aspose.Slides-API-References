---
title: get_NoBreak()
second_title: Aspose.Slides for C++ API 參考文件
description: "無斷行 此屬性指定 \"unbreakable\" 屬性於物件框上。當為 true 時，框內不會出現換行。這對於包含多個二元運算子的運算子模擬器可能很重要。若未指定此元素，框內可能會發生換行。預設值： true"
type: docs
weight: 40
url: /zh-hant/aspose.slides.mathtext/mathbox/get_nobreak/
---
## MathBox::get_NoBreak() 方法

無斷行 此屬性指定 \"unbreakable\" 屬性於物件框上。當為 true 時，框內不會產生換行。這對於包含多個二元運算子的運算子模擬器可能很重要。當未指定此元素時，框內可能會發生換行。預設值： true

```cpp
bool Aspose::Slides::MathText::MathBox::get_NoBreak() override
```

## 備註

範例： 
```cpp
auto box = System::MakeObject<MathBox>(System::MakeObject<MathematicalText>(u"*****"));
box->set_NoBreak(false);
```

## 另請參閱

* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)