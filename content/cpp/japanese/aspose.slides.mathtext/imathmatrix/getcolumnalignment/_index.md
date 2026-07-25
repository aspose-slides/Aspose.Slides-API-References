---
title: GetColumnAlignment()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定した列の水平揃えを取得します
type: docs
weight: 235
url: /ja/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) メソッド

指定した列の水平揃えを取得します

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | ゼロベースの列インデックス |

### 戻り値

指定した列の水平揃え

## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## 参照

* 列挙体 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)