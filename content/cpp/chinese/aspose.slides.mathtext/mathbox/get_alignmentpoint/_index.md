---
title: get_AlignmentPoint()
second_title: Aspose.Slides for C++ API 参考
description: "当为 true 时，此运算符仿真器充当对齐点；即，其他方程中的指定对齐点可以与其对齐。默认值：false"
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/mathbox/get_alignmentpoint/
---
## MathBox::get_AlignmentPoint() 方法


当为 true 时，此运算符仿真器充当对齐点；即，其他方程中的指定对齐点可以与其对齐。默认值：false

```cpp
bool Aspose::Slides::MathText::MathBox::get_AlignmentPoint() override
```

## 备注


示例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 另请参见

* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)