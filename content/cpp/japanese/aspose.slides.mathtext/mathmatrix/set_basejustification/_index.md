---
title: set_BaseJustification()
second_title: Aspose.Slides for C++ API リファレンス
description: "周囲のテキストに対する垂直方向の揃えを指定します。可能な値は上部、下部、中央です。デフォルト: 中央"
type: docs
weight: 66
url: /ja/aspose.slides.mathtext/mathmatrix/set_basejustification/
---
## MathMatrix::set_BaseJustification(MathVerticalAlignment) メソッド


周囲のテキストに対する垂直方向の揃えを指定します。可能な値は top、bottom、center です。デフォルト: Center

```cpp
void Aspose::Slides::MathText::MathMatrix::set_BaseJustification(MathVerticalAlignment value) override
```

## 備考


例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_BaseJustification(MathVerticalAlignment::Center);
```

## 参照

* Enum [MathVerticalAlignment](../../mathverticalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)