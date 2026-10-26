---
title: get_Denominator()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 分母
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/mathfraction/get_denominator/
---
## MathFraction::get_Denominator() メソッド


分母

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Denominator() override
```

## 備考


例: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto denominator = mathFraction->get_Denominator();
```

## 関連項目

* タイプ定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathFraction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)