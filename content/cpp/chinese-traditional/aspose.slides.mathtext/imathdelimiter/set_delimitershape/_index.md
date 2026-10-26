---
title: set_DelimiterShape()
second_title: Aspose.Slides for C++ API 參考文件
description: "指定分隔符物件中分隔符的形狀。當為 MathDelimiterShape::Centered 時，分隔符會以數學文字的數學軸為中心，並調整以符合其內容的整體高度。當為 MathDelimiterShape::Match 時，分隔符的高度和形狀會被精確調整以匹配其內容。"
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) 方法

指定分隔符物件中分隔符的形狀。當 [MathDelimiterShape::Centered](../../mathdelimitershape/) 時，分隔符會以數學文字的數學軸為中心，並調整以符合其內容的整體高度。當 [MathDelimiterShape::Match](../../mathdelimitershape/) 時，分隔符的高度和形狀會被精確調整以匹配其內容。

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
```

## 備註

範例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 另見

* 列舉 [MathDelimiterShape](../../mathdelimitershape/)
* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)