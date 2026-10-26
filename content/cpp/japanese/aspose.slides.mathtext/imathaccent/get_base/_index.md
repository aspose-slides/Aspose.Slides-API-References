---
title: get_Base()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: アクセントが適用された引数
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/imathaccent/get_base/
---
## IMathAccent::get_Base() メソッド

アクセントが適用された引数

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathAccent::get_Base()=0
```

## 備考

例:
```cpp
auto accent = System::MakeObject<MathematicalText>(u"x")->Accent(u'~');
auto baseArg = accent->get_Base();
```

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [IMathAccent](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)