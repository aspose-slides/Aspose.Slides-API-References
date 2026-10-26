---
title: get_DelimiterShape()
second_title: Aspose.Slides for C++ API 参考
description: "指定分隔符对象中分隔符的形状。当为 MathDelimiterShape::Centered 时，分隔符在数学文本的数学轴周围居中，并且仍会调整以适应其内容的整个高度。当为 MathDelimiterShape::Match 时，它们的高度和形状会被改变，以精确匹配其内容。"
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() 方法

指定分隔符对象中分隔符的形状。当 [MathDelimiterShape::Centered](../../mathdelimitershape/) 时，分隔符在数学文本的数学轴周围居中，并且仍然会调整以适应其内容的整个高度。当 [MathDelimiterShape::Match](../../mathdelimitershape/) 时，它们的高度和形状会被改变，以精确匹配其内容。

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## 备注

示例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 另请参见

* 枚举 [MathDelimiterShape](../../mathdelimitershape/)
* 类 [IMathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)