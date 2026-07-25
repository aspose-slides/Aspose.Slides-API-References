---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された列の水平方向の配置を設定します
type: docs
weight: 261
url: /ja/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) メソッド

指定した列の水平方向の配置を設定します

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 整列を設定する最初の列のゼロベースインデックス |
| columnsCount | **uint32_t** | 整列を指定する列の数 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 指定された列の水平方向の配置の新しい値 |
## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## 参照

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)