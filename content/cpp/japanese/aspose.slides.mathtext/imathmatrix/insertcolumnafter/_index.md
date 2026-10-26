---
title: InsertColumnAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された列の後に新しい列を挿入します。新しい列のすべての要素は初期状態で null です。
type: docs
weight: 326
url: /ja/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) メソッド


指定された列の後に新しい列を挿入します。新しい列のすべての要素は初期状態で null です。

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 新しい列を挿入する対象となる列のインデックス |
## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## 関連項目

* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)