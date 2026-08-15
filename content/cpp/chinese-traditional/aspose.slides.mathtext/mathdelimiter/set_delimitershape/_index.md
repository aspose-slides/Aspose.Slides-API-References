---
title: set_DelimiterShape()
second_title: Aspose.Slides for C++ API 參考
description: "指定分隔符物件中分隔符的形狀。當 MathDelimiterShape::Centered 時，分隔符會以數學文字的數學軸為中心，且仍會調整以適應其內容的整個高度。當 MathDelimiterShape::Match 時，分隔符的高度和形狀會被調整為完全匹配其內容。"
type: docs
weight: 131
url: /zh-hant/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) 方法


指定分隔符物件中分隔符的形狀。當 [MathDelimiterShape::Centered](../../mathdelimitershape/) 時，分隔符會以數學文字的數學軸為中心，且仍會調整以適應其內容的整個高度。當 [MathDelimiterShape::Match](../../mathdelimitershape/) 時，分隔符的高度和形狀會被調整為完全匹配其內容。

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## 備註


範例：
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 參見

* 列舉 [MathDelimiterShape](../../mathdelimitershape/)
* 類別 [MathDelimiter](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)