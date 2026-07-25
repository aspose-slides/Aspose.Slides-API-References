---
title: get_MinColumnWidth()
second_title: Aspose.Slides for C++ API リファレンス
description: "twips（ポイントの1/20）単位の最小列幅です。ギャップ間隔（\\u201CColumn Gap\\u201D または \\u201CGap Width\\u201D とも呼ばれます）は MinColumnWidth に加算され、総合的な Matrix 列間隔（異なる列の同じエッジ間の距離）を決定します。デフォルト: 0."
type: docs
weight: 79
url: /ja/aspose.slides.mathtext/imathmatrix/get_mincolumnwidth/
---
## IMathMatrix::get_MinColumnWidth() メソッド

最小列幅（twips 単位、ポイントの 1/20） \\u201CColumn Gap\\u201D または \\u201CGap Width\\u201D とも呼ばれるギャップ間隔は MinColumnWidth に加算され、合計 Matrix [Column](../../../aspose.slides/column/) Spacing（異なる列の同じエッジ間の距離）を決定します。 デフォルト: 0.

```cpp
virtual uint32_t Aspose::Slides::MathText::IMathMatrix::get_MinColumnWidth()=0
```

## 備考

例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->set_MinColumnWidth(20);
```

## 参照

* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)