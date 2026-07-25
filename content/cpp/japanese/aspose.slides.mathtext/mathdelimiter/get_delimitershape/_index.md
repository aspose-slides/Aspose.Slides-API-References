---
title: get_DelimiterShape()
second_title: Aspose.Slides for C++ API リファレンス
description: "区切りオブジェクト内の区切り記号の形状を指定します。MathDelimiterShape::Centered の場合、区切り記号は数式テキストの数学軸の周りに中央揃えされ、内容全体の高さに合わせてフィットするように作成されます。MathDelimiterShape::Match の場合、区切り記号の高さと形状は内容に正確に合わせるように変更されます。"
type: docs
weight: 118
url: /ja/aspose.slides.mathtext/mathdelimiter/get_delimitershape/
---
## MathDelimiter::get_DelimiterShape() メソッド

区切りオブジェクト内の区切り記号の形状を指定します。[MathDelimiterShape::Centered](../../mathdelimitershape/) の場合、区切り記号は数式テキストの数学軸の周りに中央揃えされ、内容全体の高さに合わせてフィットするように作成されます。[MathDelimiterShape::Match](../../mathdelimitershape/) の場合、区切り記号の高さと形状は内容に正確に合わせるように変更されます。

```cpp
MathDelimiterShape Aspose::Slides::MathText::MathDelimiter::get_DelimiterShape() override
```

## 備考

例:
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 関連項目

* Enum [MathDelimiterShape](../../mathdelimitershape/)
* Class [MathDelimiter](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)