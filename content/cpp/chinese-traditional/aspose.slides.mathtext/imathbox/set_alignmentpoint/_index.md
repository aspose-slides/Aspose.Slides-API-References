---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API 參考文件
description: "當值為 true 時，此運算子模擬器充當對齊點；也就是說，其他等式中指定的對齊點可以與其對齊。預設值： false"
type: docs
weight: 105
url: /zh-hant/aspose.slides.mathtext/imathbox/set_alignmentpoint/
---
## IMathBox::set_AlignmentPoint(bool) 方法

當值為 true 時，此運算子模擬器充當對齊點；也就是說，其他等式中指定的對齊點可以與其對齊。預設值： false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_AlignmentPoint(bool value)=0
```

## 備註

範例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 參見

* 類別 [IMathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)