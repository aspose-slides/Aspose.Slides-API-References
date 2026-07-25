---
title: get_DelimiterShape()
second_title: Aspose.Slides for C++ API リファレンス
description: "delimiter object の区切り記号の形状を指定します。MathDelimiterShape::Centered の場合、区切り記号は数式テキストの数式軸の周りに中央揃えされ、内容全体の高さに合わせて調整されます。MathDelimiterShape::Match の場合、其の高さと形状は内容に完全に一致するように変更されます。"
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/imathdelimiter/get_delimitershape/
---
## IMathDelimiter::get_DelimiterShape() メソッド

区切りオブジェクトの区切り記号の形状を指定します。[MathDelimiterShape::Centered](../../mathdelimitershape/) の場合、区切り記号は数式テキストの数式軸の周りに中央揃えされ、内容全体の高さに合わせて調整されます。[MathDelimiterShape::Match](../../mathdelimitershape/) の場合、其の高さと形状は内容に完全に一致するように変更されます。

```cpp
virtual MathDelimiterShape Aspose::Slides::MathText::IMathDelimiter::get_DelimiterShape()=0
```

## 備考

例: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 参照

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [IMathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)