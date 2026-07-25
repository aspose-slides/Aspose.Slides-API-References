---
title: get_HideSuperscript()
second_title: Aspose.Slides for C++ API リファレンス
description: 上付き文字を非表示にする
type: docs
weight: 105
url: /ja/aspose.slides.mathtext/imathnaryoperatorproperties/get_hidesuperscript/
---
## IMathNaryOperatorProperties::get_HideSuperscript() メソッド


上付き文字を非表示にする

```cpp
virtual bool Aspose::Slides::MathText::IMathNaryOperatorProperties::get_HideSuperscript()=0
```

## 備考


例: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSuperscript(true);
```

## 関連項目

* クラス [IMathNaryOperatorProperties](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)