---
title: get_AlignmentPoint()
second_title: Aspose.Slides for C++ API 参考
description: "当为 true 时，此运算符仿真器充当对齐点；也就是说，其他等式中指定的对齐点可以与之对齐。默认值：false"
type: docs
weight: 92
url: /zh/aspose.slides.mathtext/imathbox/get_alignmentpoint/
---
## IMathBox::get_AlignmentPoint() 方法


当为 true 时，此运算符仿真器充当对齐点；也就是说，其他等式中指定的对齐点可以与之对齐。默认值：false

```cpp
virtual bool Aspose::Slides::MathText::IMathBox::get_AlignmentPoint()=0
```

## 备注


示例： 
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
box->set_AlignmentPoint(true);
```

## 另见

* 类 [IMathBox](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)