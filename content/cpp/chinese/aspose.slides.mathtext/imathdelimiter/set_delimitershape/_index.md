---
title: set_DelimiterShape()
second_title: Aspose.Slides for C++ API 参考
description: "指定定界符对象中定界符的形状。当为 MathDelimiterShape::Centered 时，定界符居中于数学文本的数学轴，并且仍能适应其内容的整个高度。当为 MathDelimiterShape::Match 时，它们的高度和形状被调整为恰好匹配其内容。"
type: docs
weight: 131
url: /zh/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) 方法


指定定界符对象中定界符的形状。 当 [MathDelimiterShape::Centered](../../mathdelimitershape/) 时，定界符居中于数学文本的数学轴，并且仍然能够适应其内容的整个高度。 当 [MathDelimiterShape::Match](../../mathdelimitershape/) 时，它们的高度和形状被调整为恰好匹配其内容。


```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## 备注


示例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 参见

* 枚举 [MathDelimiterShape](../../mathdelimitershape/)
* 类 [IMathDelimiter](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)