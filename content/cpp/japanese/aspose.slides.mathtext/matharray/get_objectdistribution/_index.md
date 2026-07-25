---
title: get_ObjectDistribution()
second_title: Aspose.Slides for C++ API リファレンス
description: Object Distribution が true の場合、配列の内容は配列オブジェクトの最大幅に合わせて間隔が調整されます。
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/matharray/get_objectdistribution/
---
## MathArray::get_ObjectDistribution() メソッド

Object Distribution true の場合、配列の内容は配列オブジェクトの最大幅に合わせて間隔が調整されます。

```cpp
bool Aspose::Slides::MathText::MathArray::get_ObjectDistribution() override
```

## 備考

例：
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_ObjectDistribution(true);
```

## 参照

* クラス [MathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)