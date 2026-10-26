---
title: SetColumnsAlignment()
second_title: Aspose.Slides C++ API 參考
description: 設定指定欄的水平對齊方式
type: docs
weight: 261
url: /zh-hant/aspose.slides.mathtext/imathmatrix/setcolumnsalignment/
---
## IMathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) 方法


設定指定欄的水平對齊方式

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 設定對齊的第一欄的零基索引 |
| columnsCount | **uint32_t** | 要指定對齊的欄位數量 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 指定欄位水平對齊的新值 |
## 備註



範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## 另請參閱

* 列舉 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)