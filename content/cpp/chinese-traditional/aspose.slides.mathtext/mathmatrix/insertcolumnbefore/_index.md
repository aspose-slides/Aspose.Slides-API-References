---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定列之前插入新列，新的列中所有元素最初皆為 null。
type: docs
weight: 326
url: /zh-hant/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) 方法

在指定列之前插入一個新列。新列中的所有元素最初皆為 null。

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| columnIndex | **int32_t** | 在插入新列之前的列索引 |
## 備註



範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## 另見

* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)