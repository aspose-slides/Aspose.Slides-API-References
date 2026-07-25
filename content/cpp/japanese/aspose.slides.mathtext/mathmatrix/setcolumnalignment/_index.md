---
title: SetColumnAlignment()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された列の水平揃えを設定します
type: docs
weight: 261
url: /ja/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) メソッド

指定された列の水平揃えを設定します

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 0ベースの列インデックス |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 指定された列の水平揃えの新しい値 |

## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## 参照

* 列挙 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)