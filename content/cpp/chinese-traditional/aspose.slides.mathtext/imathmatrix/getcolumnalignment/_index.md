---
title: GetColumnAlignment()
second_title: Aspose.Slides for C++ API 參考文件
description: 取得指定欄位的水平對齊方式
type: docs
weight: 235
url: /zh-hant/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) 方法

取得指定欄位的水平對齊方式

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 以零為起始的欄位索引 |

### 回傳值

指定欄位的水平對齊方式
## 備註



範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## 另請參閱

* 列舉 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)