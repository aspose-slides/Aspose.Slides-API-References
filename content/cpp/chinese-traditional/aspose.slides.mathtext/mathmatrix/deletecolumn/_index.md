---
title: DeleteColumn()
second_title: Aspose.Slides 的 C++ API 參考
description: 刪除指定的列
type: docs
weight: 352
url: /zh-hant/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix::DeleteColumn(int32_t) 方法


刪除指定的列

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteColumn(int32_t columnIndex) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 要刪除的列的零基索引。 |
## 備註



範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## 另請參閱

* 類別 [MathMatrix](../)
* 名稱空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)