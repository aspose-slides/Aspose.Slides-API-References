---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API 參考
description: "當為 true 時，此運算子模擬器充當對齊點；也就是說，其他等式中指定的對齊點可以與之對齊。預設值：false"
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/mathbox/set_alignmentpoint/
---
## MathBox::set_AlignmentPoint(bool) 方法


當為 true 時，此運算子模擬器充當對齊點；也就是說，其他等式中指定的對齊點可以與之對齊。預設值：false

```cpp
void Aspose::Slides::MathText::MathBox::set_AlignmentPoint(bool value) override
```

## 備註


範例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 另請參閱

* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)