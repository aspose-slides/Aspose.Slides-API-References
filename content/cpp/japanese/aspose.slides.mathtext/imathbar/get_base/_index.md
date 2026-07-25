---
title: get_Base()
second_title: Aspose.Slides for C++ API リファレンス
description: Base 引数
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathbar/get_base/
---
## IMathBar::get_Base() メソッド

Base 引数

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBar::get_Base()=0
```

## 備考


例: 
```cpp
auto mathBar = System::MakeObject<MathBar>(System::MakeObject<MathematicalText>(u"x"));
auto baseArg = mathBar->get_Base();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathBar](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)