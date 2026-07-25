---
title: set_HideSubscript()
second_title: Aspose.Slides の C++ API リファレンス
description: サブスクリプトを非表示
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/imathnaryoperatorproperties/set_hidesubscript/
---
## IMathNaryOperatorProperties::set_HideSubscript(bool) メソッド


サブスクリプトを非表示

```cpp
virtual void Aspose::Slides::MathText::IMathNaryOperatorProperties::set_HideSubscript(bool value)=0
```

## 備考


例: 
```cpp
auto naryOperator = System::MakeObject<MathematicalText>(u"x")->Nary(MathNaryOperatorTypes::Summation, u"x=1", u"100");
naryOperator->set_HideSubscript(true);
```

## 関連項目

* クラス [IMathNaryOperatorProperties](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)