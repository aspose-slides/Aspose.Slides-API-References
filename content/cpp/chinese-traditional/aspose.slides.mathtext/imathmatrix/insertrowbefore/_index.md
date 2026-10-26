---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API 參考
description: 在指定行之前插入新行。新行中的所有元素最初為 null。
type: docs
weight: 274
url: /zh-hant/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) method


在指定行之前插入新行。新行中的所有元素最初為 null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```


### Arguments

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 要在其之前插入新行的行索引 |
## 備註



範例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## 另見

* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)