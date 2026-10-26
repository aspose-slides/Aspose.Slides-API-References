---
title: GetColumnAlignment()
second_title: Aspose.Slides for C++ API 參考
description: 取得指定欄位的水平對齊方式
type: docs
weight: 248
url: /zh-hant/aspose.slides.mathtext/mathmatrix/getcolumnalignment/
---
## MathMatrix::GetColumnAlignment(int32_t) 方法


取得指定欄位的水平對齊方式

```cpp
MathHorizontalAlignment Aspose::Slides::MathText::MathMatrix::GetColumnAlignment(int32_t columnIndex) override
```


### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | 以零為起點的欄位索引 |

### 傳回值

指定欄位的水平對齊方式
## 備註



範例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## 參見

* Enum [MathHorizontalAlignment](../../mathhorizontalalignment/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)