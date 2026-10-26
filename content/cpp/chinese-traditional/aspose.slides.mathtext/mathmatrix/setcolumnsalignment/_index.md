---
title: SetColumnsAlignment()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定指定欄位的水平對齊方式
type: docs
weight: 274
url: /zh-hant/aspose.slides.mathtext/mathmatrix/setcolumnsalignment/
---
## MathMatrix::SetColumnsAlignment(int32_t, uint32_t, MathHorizontalAlignment) 方法


設定指定欄位的水平對齊方式

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnsAlignment(int32_t columnIndex, uint32_t columnsCount, MathHorizontalAlignment val) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 設定對齊的第一個欄位之零基索引 |
| columnsCount | **uint32_t** | 要指定對齊方式的欄位數量 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 指定欄位之水平對齊的新值 |
## 備註



範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnsAlignment(0, 3, MathHorizontalAlignment::Left);
```

## 另請參閱

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)