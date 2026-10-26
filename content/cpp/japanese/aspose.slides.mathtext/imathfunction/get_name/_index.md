---
title: get_Name()
second_title: Aspose.Slides for C++ API リファレンス
description: 関数名 例えば、関数名は sin と cos です
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathfunction/get_name/
---
## IMathFunction::get_Name() メソッド

関数名 例えば、関数名は sin と cos です

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathFunction::get_Name()=0
```

## 備考

例:
```cpp
auto func = System::MakeObject<MathematicalText>(u"sin")->Function(u"x");
auto funcName = func->get_Name();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathFunction](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)