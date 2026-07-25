---
title: set_DelimiterShape()
second_title: Aspose.Slides for C++ APIリファレンス
description: "区切りオブジェクト内のデリミタの形状を指定します。MathDelimiterShape::Centered の場合、デリミタは数式テキストの数学軸の周りにセンタリングされ、内容全体の高さに合わせて調整されます。MathDelimiterShape::Match の場合、高さと形状は内容に完全に一致するように変更されます。"
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/imathdelimiter/set_delimitershape/
---
## IMathDelimiter::set_DelimiterShape(MathDelimiterShape) メソッド


区切りオブジェクト内のデリミタの形状を指定します。[MathDelimiterShape::Centered](../../mathdelimitershape/) の場合、デリミタは数式テキストの数学軸の周りにセンタリングされ、内容全体の高さに合わせて調整されます。[MathDelimiterShape::Match](../../mathdelimitershape/) の場合、高さと形状は内容に完全に一致するように変更されます。

```cpp
virtual void Aspose::Slides::MathText::IMathDelimiter::set_DelimiterShape(MathDelimiterShape value)=0
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