---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API 參考
description: 在指定的行之前插入新行。新行中的所有元素最初為 null。
type: docs
weight: 287
url: /zh-hant/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) method

在指定的行之前插入新行。新行中的所有元素最初為 null。

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 要在其前插入新行的行的索引 |

## 備註



範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## 參見

* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)