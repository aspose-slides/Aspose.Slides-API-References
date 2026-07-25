---
title: get_Base()
second_title: Aspose.Slides for C++ API リファレンス
description: 関数引数
type: docs
weight: 14
url: /ja/aspose.slides.mathtext/imathfunction/get_base/
---
## IMathFunction::get_Base() メソッド

Function Argument

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Base()=0
```

## 備考

Example: 
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto baseArg = func->get_Base();
```

## 参照

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathFunction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)