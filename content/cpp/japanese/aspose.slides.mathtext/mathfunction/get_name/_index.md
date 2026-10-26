---
title: get_Name()
second_title: Aspose.Slides for C++ API リファレンス
description: 関数名 例として、関数名は sin と cos です
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathfunction/get_name/
---
## MathFunction::get_Name() メソッド

関数名 例として、関数名は sin と cos です

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathFunction::get_Name() override
```

## 備考

例:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathFunction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)