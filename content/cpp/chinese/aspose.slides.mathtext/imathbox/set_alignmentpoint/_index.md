---
title: set_AlignmentPoint()
second_title: Aspose.Slides for C++ API 参考
description: "当设为 true 时，此运算符仿真器充当对齐点；也就是说，其他等式中的指定对齐点可以与其对齐。默认值：false"
type: docs
weight: 105
url: /zh/aspose.slides.mathtext/imathbox/set_alignmentpoint/
---
## IMathBox::set_AlignmentPoint(bool) 方法

当为 true 时，此运算符仿真器充当对齐点；也就是说，其他等式中的指定对齐点可以与其对齐。默认值：false

```cpp
virtual void Aspose::Slides::MathText::IMathBox::set_AlignmentPoint(bool value)=0
```

## 备注

示例：
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 另请参阅

* 类 [IMathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)