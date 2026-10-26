---
title: get_DelimiterShape()
second_title: Aspose.Slides for C++ API 參考手冊
description: "指定分隔符物件中分隔符的形狀。當為 MathDelimiterShape::Centered 時，分隔符會以數學文字的數學軸為中心，且仍會調整以符合其內容的整個高度。當為 MathDelimiterShape::Match 時，會將其高度和形狀變更為完全匹配其內容。"
type: docs
weight: 118
url: /zh-hant/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() method


指定分隔符物件中分隔符的形狀。當為 [MathDelimiterShape::Centered](../../mathdelimitershape/) 時，分隔符會以數學文字的數學軸為中心，且仍會調整以符合其內容的整個高度。當為 [MathDelimiterShape::Match](../../mathdelimitershape/) 時，會將其高度和形狀變更為完全匹配其內容。

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## 備註


範例： 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 另請參閱

* 列舉 [MathDelimiterShape](../../mathdelimitershape/)
* 類別 [IMathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)