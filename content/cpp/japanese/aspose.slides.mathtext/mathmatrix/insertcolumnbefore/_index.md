---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された列の前に新しい列を挿入します。新しい列のすべての要素は null です。
type: docs
weight: 326
url: /ja/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) メソッド

指定した列の前に新しい列を挿入します。新しい列のすべての要素は null です。

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 新しい列を挿入する前の列のインデックス |

## 備考



例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## 参照

* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)