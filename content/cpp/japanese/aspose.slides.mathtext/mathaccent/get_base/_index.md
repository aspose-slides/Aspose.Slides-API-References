---
title: get_Base()
second_title: Aspose.Slides for C++ API リファレンス
description: アクセントが適用された引数
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathaccent/get_base/
---
## MathAccent::get_Base() メソッド

アクセントが適用された引数

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathAccent::get_Base() override
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
* クラス [MathAccent](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)