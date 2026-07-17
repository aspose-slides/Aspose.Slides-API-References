---
title: get_BaseJustification()
second_title: Aspose.Slides C++ API 参考
description: "指定相对于周围文本的垂直对齐方式。可能的取值为 top、bottom 和 center。默认值：Center"
type: docs
weight: 53
url: /zh/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() method


指定相对于周围文本的垂直对齐方式。可能的取值为 top、bottom 和 center。默认值：Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## 备注


示例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 另请参见

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)