---
title: get_AlignmentPoint()
second_title: Aspose.Slides for C++ API 參考
description: "當為 true 時，此運算子模擬器作為對齊點；也就是說，其他方程式中指定的對齊點可以與它對齊。預設值: false"
type: docs
weight: 92
url: /zh-hant/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() 方法


當為 true 時，此運算子模擬器作為對齊點；也就是說，其他方程式中指定的對齊點可以與它對齊。預設值: false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## 備註


範例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 另請參閱

* 類別 [IMathBox](../)
* 名稱空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)