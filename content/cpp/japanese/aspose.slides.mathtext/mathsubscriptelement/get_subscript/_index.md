---
title: get_Subscript()
second_title: Aspose.Slides for C++ API リファレンス
description: 下付き文字
type: docs
weight: 1
url: /ja/aspose.slides.mathtext/mathsubscriptelement/get_subscript/
---
## MathSubscriptElement::get_Subscript() メソッド

下付き文字

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathSubscriptElement::get_Subscript() override
```

## 備考

例:
```cpp
auto baseElement = System::MakeObject<MathematicalText>(u"X");
auto subscript = System::MakeObject<MathematicalText>(u"i");
auto subscriptElement = System::MakeObject<MathSubscriptElement>(baseElement, subscript);
auto sub = subscriptElement->get_Subscript();
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IMathElement](../../imathelement/)
* クラス [MathSubscriptElement](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)