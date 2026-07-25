---
title: get_Base()
second_title: Aspose.Slides for C++ API リファレンス
description: Base 引数
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathbox/get_base/
---
## IMathBox::get_Base() メソッド

Base 引数

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathBox::get_Base()=0
```

## 備考

例:
```cpp
auto box = System::MakeObject<MathematicalText>(u"==")->ToBox();
auto baseArg = box->get_Base();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathBox](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)