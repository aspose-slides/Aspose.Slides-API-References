---
title: get_Base()
second_title: Aspose.Slides for C++ API リファレンス
description: 関数引数
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/mathfunction/get_base/
---
## MathFunction::get_Base() メソッド


関数引数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Base() override
```

## 備考


例: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathFunction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)