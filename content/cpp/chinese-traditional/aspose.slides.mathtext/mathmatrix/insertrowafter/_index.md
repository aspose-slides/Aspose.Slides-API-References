---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API 參考
description: 在指定的行之後插入新行，新的行中所有元素最初皆為 null。
type: docs
weight: 300
url: /zh-hant/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) 方法

在指定的行之後插入新行，新的行中所有元素最初皆為 null。

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 在其之後插入新列的索引 |
## 備註



範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## 參見

* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)