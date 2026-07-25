---
title: get_MaximumDistribution()
second_title: Aspose.Slides for C++ API リファレンス
description: 最大分布 真の場合、配列は含まれる要素（ページ、列、セルなど）の最大幅に合わせて間隔が設定されます。
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/imatharray/get_maximumdistribution/
---
## IMathArray::get_MaximumDistribution() メソッド

最大分布 true の場合、配列は含まれる要素 (ページ、列、セル、など) の最大幅に合わせて間隔が設定されます。

```cpp
virtual bool Aspose::Slides::MathText::IMathArray::get_MaximumDistribution()=0
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