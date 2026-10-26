---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API 参考
description: "指定相对于周围文本的垂直对齐方式。可能的取值有 top、bottom 和 center。默认值：Center"
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/imathmatrix/set_basejustification/
---
## IMathMatrix::set_BaseJustification(MathVerticalAlignment) 方法

指定相对于周围文本的垂直对齐方式。可能的取值有 top、bottom 和 center。默认值：Center

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_BaseJustification(MathVerticalAlignment value)=0
```

## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 另请参阅

* 枚举 [MathVerticalAlignment](../../mathverticalalignment/)
* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)