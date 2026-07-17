---
title: set_DelimiterShape()
second_title: Aspose.Slides for C++ API 参考
description: "指定分隔符对象中分隔符的形状。当为 MathDelimiterShape::Centered 时，分隔符在数学文本的数学轴周围居中，并且仍然会被调整以适应其内容的整体高度。当为 MathDelimiterShape::Match 时，它们的高度和形状会被更改，以精确匹配其内容。"
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) 方法


指定分隔符对象中分隔符的形状。当为 [MathDelimiterShape::Centered](../../mathdelimitershape/) 时，分隔符在数学文本的数学轴周围居中，并且仍然会被调整以适应其内容的整体高度。当为 [MathDelimiterShape::Match](../../mathdelimitershape/) 时，它们的高度和形状会被更改，以精确匹配其内容。

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## 备注


示例: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 另请参阅

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)