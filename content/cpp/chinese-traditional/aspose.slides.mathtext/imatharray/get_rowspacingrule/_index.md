---
title: get_RowSpacingRule()
second_title: Aspose.Slides for C++ API 參考
description: 陣列元素之間的垂直間距類型
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/imatharray/get_rowspacingrule/
---
## IMathArray::get_RowSpacingRule() 方法


陣列元素之間的垂直間距類型

```cpp
virtual MathRowSpacingRule Aspose::Slides::MathText::IMathArray::get_RowSpacingRule()=0
```

## 備註


範例： 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_RowSpacingRule(MathRowSpacingRule::OneAndAHalfLineGap);
```

## 另請參閱

* 列舉 [MathRowSpacingRule](../../mathrowspacingrule/)
* 類別 [IMathArray](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)