---
title: InsertColumnAfter()
second_title: Aspose.Slides for C++ API 參考
description: 在指定的欄位之後插入新欄，新的欄位中所有元素最初皆為 null.
type: docs
weight: 339
url: /zh-hant/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) 方法


在指定欄位之後插入新欄，新的欄位中所有元素最初皆為 null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 在此之後插入新欄位的欄索引 |
## 備註



範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## 參見

* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)