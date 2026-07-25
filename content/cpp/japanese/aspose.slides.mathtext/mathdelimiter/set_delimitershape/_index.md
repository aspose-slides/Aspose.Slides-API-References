---
title: set_DelimiterShape()
second_title: Aspose.Slides for C++ API リファレンス
description: "区切りオブジェクト内のデリミタの形状を指定します。MathDelimiterShape::Centered の場合、デリミタは数式テキストの数学軸の周りにセンタリングされ、内容全体の高さに合わせて調整されます。MathDelimiterShape::Match の場合、デリミタの高さと形状は内容に正確に一致するように変更されます。"
type: docs
weight: 131
url: /ja/aspose.slides.mathtext/mathdelimiter/set_delimitershape/
---
## MathDelimiter::set_DelimiterShape(MathDelimiterShape) メソッド

区切りオブジェクト内のデリミタの形状を指定します。[MathDelimiterShape::Centered](../../mathdelimitershape/) の場合、デリミタは数式テキストの数学軸の周りにセンタリングされ、内容全体の高さに合わせて調整されます。[MathDelimiterShape::Match](../../mathdelimitershape/) の場合、デリミタの高さと形状は内容に正確に一致するように変更されます。

```cpp
void Aspose::Slides::MathText::MathDelimiter::set_DelimiterShape(MathDelimiterShape value) override
```

## 備考


例: 
```cpp
auto delimiter = System::MakeObject<MathematicalText>(u"x")->Divide(u"y")->Enclose();
delimiter->set_DelimiterShape(MathDelimiterShape::Match);
```

## 参照

* 列挙体 [MathDelimiterShape](../../mathdelimitershape/)
* クラス [MathDelimiter](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)