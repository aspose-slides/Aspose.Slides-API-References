---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定した列の前に新しい列を挿入します。新しい列のすべての要素は初期状態で null です。
type: docs
weight: 313
url: /ja/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) メソッド


指定した列の前に新しい列を挿入します。新しい列のすべての要素は初期状態で null です。

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 挿入する新しい列の前の列のインデックス |
## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## 参照

* クラス [IMathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* ライブラリ [Aspose.Slides](../../../)