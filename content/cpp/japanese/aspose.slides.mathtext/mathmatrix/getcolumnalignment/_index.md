---
title: GetColumnAlignment()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された列の水平配置を取得します
type: docs
weight: 248
url: /ja/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) メソッド

指定された列の水平配置を取得します

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | **int32_t** | ゼロベースの列インデックス |

### 戻り値

指定された列の水平揃え

## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## 参照

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)