---
title: DeleteRow()
second_title: Aspose.Slides for C++ API 參考
description: 刪除指定的列
type: docs
weight: 300
url: /zh-hant/aspose.slides.mathtext/imathmatrix/deleterow/
---
## IMathMatrix::DeleteRow(int32_t) 方法


刪除指定的列

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteRow(int32_t rowIndex)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 要刪除之列的零基索引。 |
## 備註



範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## 另見

* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)