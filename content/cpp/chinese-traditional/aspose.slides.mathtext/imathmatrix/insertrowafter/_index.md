---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API 參考
description: 在指定的列之後插入新列。新列中的所有元素最初皆為 null。
type: docs
weight: 287
url: /zh-hant/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) 方法


在指定的列之後插入新列。新列中的所有元素最初皆為 null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 要在其後插入新列的列索引 |
## 備註



範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## 另請參閱

* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)