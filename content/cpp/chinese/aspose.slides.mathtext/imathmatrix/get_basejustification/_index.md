---
title: get_BaseJustification()
second_title: Aspose.Slides C++ API 参考
description: "指定相对于周围文本的垂直对齐方式。可能的取值为 top、bottom 和 center。默认：Center"
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/imathmatrix/get_basejustification/
---
## IMathMatrix::get_BaseJustification() 方法

指定相对于周围文本的垂直对齐方式。可能的取值为 top、bottom 和 center。默认：Center

```cpp
virtual MathVerticalAlignment Aspose::Slides::MathText::IMathMatrix::get_BaseJustification()=0
```

## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 另见

* 枚举 [MathVerticalAlignment](../../mathverticalalignment/)
* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)