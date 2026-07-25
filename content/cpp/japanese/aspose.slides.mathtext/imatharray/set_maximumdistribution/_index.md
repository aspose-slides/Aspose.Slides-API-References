---
title: set_MaximumDistribution()
second_title: Aspose.Slides for C++ APIリファレンス
description: true の場合、配列は含まれる要素（ページ、列、セルなど）の最大幅になるように間隔が調整されます。
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/imatharray/set_maximumdistribution/
---
## IMathArray::set_MaximumDistribution(bool) メソッド


Maximum Distribution が true の場合、配列は含まれる要素（ページ、列、セルなど）の最大幅になるように間隔が調整されます。

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_MaximumDistribution(bool value)=0
```

## 備考


例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_MaximumDistribution(true);
```

## 参照

* クラス [IMathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)