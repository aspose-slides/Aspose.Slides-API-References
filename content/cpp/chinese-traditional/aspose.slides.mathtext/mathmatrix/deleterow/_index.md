---
title: DeleteRow()
second_title: Aspose.Slides C++ API 參考
description: 刪除指定的列
type: docs
weight: 313
url: /zh-hant/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) 方法

刪除指定的列

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 要刪除的列之零基索引。 |
## 備註



範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## 另請參見

* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 程式庫 [Aspose.Slides](../../../)