---
title: MathSpacingRules
second_title: Aspose.Slides for C++ API リファレンス
description: 行列の列間のギャップ（水平間隔）の種類
type: docs
weight: 1288
url: /ja/aspose.slides.mathtext/mathspacingrules/
---
## MathSpacingRules 列挙型

行列の列間のギャップ（水平間隔）の種類

```cpp
enum class MathSpacingRules
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| SingleSpacingGap | 0 | 単一（列は 1 em、行は 1 行） |
| OneAndHalfSpacingGap | 1 | 1.5 倍（列は 1.5 em、行は 1.5 行） |
| DoubleSpacingGap | 2 | 二重間隔（列は 2 em、行は 2 行） |
| Exactly | 3 | 正確な値。列の場合は ColumnGap の値（twips 単位）に依存し、行の場合は RowGap の値（twips 単位）に依存します |
| Multiple | 4 | 複数。列の場合は ColumnGap の値を 0.5 em の増分で測定し、行の場合は RowGap の値を行単位で測定します |

## 関連項目

* 名前空間 [Aspose::Slides::MathText](../)
* ライブラリ [Aspose.Slides](../../)