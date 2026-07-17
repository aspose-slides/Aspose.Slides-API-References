---
title: get_DelimiterShape()
second_title: Aspose.Slides C++ API 参考
description: "指定定界符对象中定界符的形状。当为 MathDelimiterShape::Centered 时，定界符在数学文本的数学轴周围居中，并且仍会调整以适应其内容的整体高度。当为 MathDelimiterShape::Match 时，其高度和形状会被更改，以精确匹配其内容。"
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() 方法

指定定界符对象中定界符的形状。当为 [MathDelimiterShape::Centered](../../mathdelimitershape/) 时，定界符会在数学文本的数学轴周围居中，并且仍会调整以适应其内容的整体高度。当为 [MathDelimiterShape::Match](../../mathdelimitershape/) 时，其高度和形状会被更改，以精确匹配其内容。

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## 备注

示例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 参见

* 枚举 [MathDelimiterShape](../../mathdelimitershape/)
* 类 [MathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)