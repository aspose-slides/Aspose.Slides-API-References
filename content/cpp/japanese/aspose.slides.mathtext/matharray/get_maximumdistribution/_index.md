---
title: get_MaximumDistribution()
second_title: Aspose.Slides for C++ API リファレンス
description: Maximum Distribution が true の場合、配列は containing element（ページ、列、セルなど）の最大幅に合わせて配置されます。
type: docs
weight: 40
url: /ja/aspose.slides.mathtext/matharray/get_maximumdistribution/
---
## MathArray::get_MaximumDistribution() メソッド


Maximum Distribution が true の場合、配列は containing element（ページ、列、セルなど）の最大幅に合わせて配置されます。

```cpp
bool Aspose::Slides::MathText::MathArray::get_MaximumDistribution() override
```

## 備考


例: 
```cpp
auto mathArray = System::MakeObject<MathArray>(System::MakeObject<MathematicalText>(u"item1"));
mathArray->set_MaximumDistribution(true);
```

## 参照

* クラス [MathArray](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)