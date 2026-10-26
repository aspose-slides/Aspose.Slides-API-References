---
title: get_AlignmentPoint()
second_title: Aspose.Slides for C++ API 參考文件
description: "當設定為 true 時，此運算子模擬器將作為對齊點；也就是說，其他方程式中指定的對齊點可以與其對齊。預設值：false"
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() 方法

當設定為 true 時，此運算子模擬器將作為對齊點；也就是說，其他方程式中指定的對齊點可以與其對齊。預設值：false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## 備註

範例：
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 另見

* 類別 [MathBox](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)