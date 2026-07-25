---
title: set_ObjectDistribution()
second_title: Aspose.Slides for C++ API リファレンス
description: Object Distribution が true の場合、配列の内容は配列オブジェクトの最大幅に合わせて間隔が調整されます。
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/imatharray/set_objectdistribution/
---
## IMathArray::set_ObjectDistribution(bool) メソッド

Object Distribution が true の場合、配列の内容は配列オブジェクトの最大幅に合わせて間隔が調整されます。

```cpp
virtual void Aspose::Slides::MathText::IMathArray::set_ObjectDistribution(bool value)=0
```

## 備考

例:
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_ObjectDistribution(true);
```

## 参照

* クラス [IMathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)