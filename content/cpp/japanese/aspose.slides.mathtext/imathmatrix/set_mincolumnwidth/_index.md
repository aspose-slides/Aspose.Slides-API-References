---
title: set_MinColumnWidth()
second_title: Aspose.Slides for C++ API リファレンス
description: "ツイップ (1/20ポイント) の最小列幅 ギャップ間隔 (\\u201CColumn Gap\\u201D または \\u201CGap Width\\u201D とも呼ばれる) は MinColumnWidth に加算され、全体の Matrix Column Spacing (異なる列の同じエッジ間の距離) を決定します。 デフォルト: 0."
type: docs
weight: 92
url: /ja/aspose.slides.mathtext/imathmatrix/set_mincolumnwidth/
---
## IMathMatrix::set_MinColumnWidth(uint32_t) メソッド


最小列幅（ツイップ (1/20ポイント)） ギャップ間隔（\\u201CColumn Gap\\u201D または \\u201CGap Width\\u201D とも呼ばれる）は MinColumnWidth に加算され、全体の Matrix [Column](../../../aspose.slides/column/) Spacing（異なる列の同じエッジ間の距離）を決定します。 デフォルト: 0.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::set_MinColumnWidth(uint32_t value)=0
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