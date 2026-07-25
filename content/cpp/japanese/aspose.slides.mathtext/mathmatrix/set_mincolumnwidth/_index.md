---
title: set_MinColumnWidth()
second_title: Aspose.Slides for C++ API リファレンス
description: "ツィップ単位（1ポイントの20分の1）での最小列幅。ギャップ間隔（\\u201CColumn Gap\\u201D または \\u201CGap Width\\u201D とも呼ばれる）は MinColumnWidth に加算され、合計 Matrix Column Spacing（異なる列の同じエッジ間の距離）を決定します。デフォルト: 0."
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/mathmatrix/set_mincolumnwidth/
---
## MathMatrix::set_MinColumnWidth(uint32_t) メソッド

最小列幅（ツィップ単位、1ポイントの20分の1）。ギャップ間隔（「Column Gap」または「Gap Width」とも呼ばれる）は MinColumnWidth に加算され、合計 Matrix [Column](../../../aspose.slides/column/) Spacing（異なる列の同じエッジ間の距離）を決定します。デフォルト: 0。

```cpp
void Aspose::Slides::MathText::MathMatrix::set_MinColumnWidth(uint32_t value) override
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