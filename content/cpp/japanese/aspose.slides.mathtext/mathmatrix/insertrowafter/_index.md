---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定した行の後に新しい行を挿入します。新しい行のすべての要素は最初は null です。
type: docs
weight: 300
url: /ja/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) メソッド


指定した行の後に新しい行を挿入します。新しい行のすべての要素は最初は null です。

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 新しい行を挿入する対象となる行のインデックス |
## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## 参照

* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)