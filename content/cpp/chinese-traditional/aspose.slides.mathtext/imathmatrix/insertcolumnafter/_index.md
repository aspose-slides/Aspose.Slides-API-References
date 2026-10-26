---
title: InsertColumnAfter()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定的欄位之後插入新欄位，新的欄位中所有元素最初皆為 null。
type: docs
weight: 326
url: /zh-hant/aspose.slides.mathtext/imathmatrix/insertcolumnafter/
---
## IMathMatrix::InsertColumnAfter(int32_t) 方法


在指定欄位之後插入新欄，新的欄位中的所有元素最初皆為 null。

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnAfter(int32_t columnIndex)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| columnIndex | **int32_t** | 要在其之後插入新欄的欄位索引 |
## 備註



範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## 另請參閱

* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)