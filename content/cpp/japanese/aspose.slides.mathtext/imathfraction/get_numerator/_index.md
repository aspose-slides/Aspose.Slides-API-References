---
title: get_Numerator()
second_title: Aspose.Slides for C++ API リファレンス
description: 分子
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/imathfraction/get_numerator/
---
## IMathFraction::get_Numerator() メソッド

分子

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Numerator()=0
```

## 備考

例:
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathFraction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)