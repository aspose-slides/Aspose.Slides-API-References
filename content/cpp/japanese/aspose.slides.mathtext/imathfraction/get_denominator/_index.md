---
title: get_Denominator()
second_title: Aspose.Slides for C++ API リファレンス
description: 分母
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/imathfraction/get_denominator/
---
## IMathFraction::get_Denominator() メソッド


分母

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFraction::get_Denominator()=0
```

## 備考


例: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathFraction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)