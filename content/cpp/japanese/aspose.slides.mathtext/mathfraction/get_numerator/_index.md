---
title: get_Numerator()
second_title: Aspose.Slides for C++ APIリファレンス
description: 分子
type: docs
weight: 27
url: /ja/aspose.slides.mathtext/mathfraction/get_numerator/
---
## MathFraction::get_Numerator() メソッド


分子

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFraction::get_Numerator() override
```

## 備考


例: 
```cpp
auto mathFraction = System::MakeObject<MathematicalText>(u"x")->Divide(u"y");
auto numerator = mathFraction->get_Numerator();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathFraction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)