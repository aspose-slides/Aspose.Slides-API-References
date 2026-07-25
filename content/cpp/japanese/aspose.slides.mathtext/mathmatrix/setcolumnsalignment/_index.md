---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定した列の水平揃えを設定します
type: docs
weight: 274
url: /ja/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) メソッド


指定した列の水平揃えを設定します

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 揃えを設定する最初の列のゼロベースインデックス |
| columnsCount | **uint32_t** | 揃えを指定する列の数 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 指定した列の水平揃えの新しい値 |
## 備考



例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## 参照

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* クラス [MathMatrix](../)
* 名前空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)