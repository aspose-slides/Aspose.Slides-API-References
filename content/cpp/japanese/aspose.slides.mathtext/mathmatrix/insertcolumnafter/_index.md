---
title: InsertColumnAfter()
second_title: Aspose.Slides の C++ 用 API リファレンス
description: 指定された列の後に新しい列を挿入します。新しい列のすべての要素は初期状態で null です。
type: docs
weight: 339
url: /ja/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) メソッド

指定された列の後に新しい列を挿入します。新しい列のすべての要素は初期状態で null です。

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 新しい列を挿入する列のインデックス |

## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## 参照

* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)