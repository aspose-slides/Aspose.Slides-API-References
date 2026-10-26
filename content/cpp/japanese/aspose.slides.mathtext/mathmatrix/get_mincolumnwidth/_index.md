---
title: get_MinColumnWidth()
second_title: Aspose.Slides for C++ API リファレンス
description: "ツイプ（1ポイントの20分の1）での最小列幅です。ギャップ間隔（\\u201CColumn Gap\\u201D または \\u201CGap Width\\u201D とも呼ばれる）は MinColumnWidth に加算され、合計マトリックス列間隔（異なる列の同じ端間の距離）を決定します。デフォルト: 0."
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/mathmatrix/get_mincolumnwidth/
---
## MathMatrix::get_MinColumnWidth() メソッド

ツイプ（1ポイントの20分の1）での最小列幅。ギャップ間隔（\\u201CColumn Gap\\u201D または \\u201CGap Width\\u201D とも呼ばれる）は MinColumnWidth に加算され、合計マトリックス [Column](../../../aspose.slides/column/) の間隔（異なる列の同じ端間の距離）を決定します。デフォルト: 0.

```cpp
uint32_t Aspose::Slides::MathText::MathMatrix::get_MinColumnWidth() override
```

## 備考


例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 参照

* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)