---
title: set_BaseJustification()
second_title: Aspose.Slides C++ API 参考
description: "指定相对于周围文本的垂直对齐方式。可能的取值为 top、bottom 和 center。默认值：Center"
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) 方法


指定相对于周围文本的垂直对齐方式。可能的取值为 top、bottom 和 center。默认值：Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## 备注


示例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 另请参阅

* 枚举 [MathVerticalAlignment](../../mathverticalalignment/)
* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)