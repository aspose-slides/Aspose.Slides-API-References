---
title: get_BaseJustification()
second_title: Aspose.Slides for C++ API リファレンス
description: "周囲のテキストに対する垂直方向の配置を指定します。可能な値は top、bottom、center です。デフォルト: Center"
type: docs
weight: 53
url: /ja/aspose.slides.mathtext/mathmatrix/get_basejustification/
---
## MathMatrix::get_BaseJustification() メソッド

周囲のテキストに対する垂直方向の配置を指定します。可能な値は top、bottom、center です。デフォルト: Center

```cpp
MathVerticalAlignment Aspose::Slides::MathText::MathMatrix::get_BaseJustification() override
```

## 備考

例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 参照

* 列挙体 [MathVerticalAlignment](../../mathverticalalignment/)
* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)