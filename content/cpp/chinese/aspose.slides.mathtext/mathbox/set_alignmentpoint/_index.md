---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API 参考
description: "当为 true 时，此运算符仿真器充当对齐点；也就是说，其他等式中指定的对齐点可以与其对齐。默认值： false"
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/mathbox/set_alignmentpoint/
---
## MathBox::set_AlignmentPoint(bool) 方法

当为 true 时，此运算符仿真器充当对齐点；也就是说，其他等式中指定的对齐点可以与其对齐。默认值： false

```cpp
void Aspose::Slides::MathText::MathBox::set_AlignmentPoint(bool value) override
```

## 备注

示例：
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 另请参阅

* 类 [MathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)