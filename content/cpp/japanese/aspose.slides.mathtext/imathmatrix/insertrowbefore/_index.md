---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された行の前に新しい行を挿入します。新しい行のすべての要素は最初は null です。
type: docs
weight: 274
url: /ja/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) メソッド

指定された行の前に新しい行を挿入します。新しい行のすべての要素は最初は null です。

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 新しい行を挿入する対象となる行のインデックス |
## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## 参照

* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)