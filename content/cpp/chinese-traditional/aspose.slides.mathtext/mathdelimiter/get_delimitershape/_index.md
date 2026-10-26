---
title: get_DelimiterShape()
second_title: Aspose.Slides for C++ API 參考
description: "指定分隔符物件中分隔符的形狀。當為 MathDelimiterShape::Centered 時，分隔符會以數學文字的數學軸為中心，並仍然調整以符合其內容的整個高度。當為 MathDelimiterShape::Match 時，會將它們的高度和形狀調整為與內容完全匹配。"
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() 方法

指定分隔符物件中分隔符的形狀。當 [MathDelimiterShape::Centered](../../mathdelimitershape/) 時，分隔符會以數學文字的數學軸為中心，並仍然調整以符合其內容的整個高度。當 [MathDelimiterShape::Match](../../mathdelimitershape/) 時，會將它們的高度和形狀調整為與內容完全匹配。

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## 備註

範例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 另請參閱

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)