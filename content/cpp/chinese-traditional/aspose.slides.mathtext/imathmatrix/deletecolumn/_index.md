---
title: DeleteColumn()
second_title: Aspose.Slides C++ API 參考文件
description: 刪除指定的欄位
type: docs
weight: 339
url: /zh-hant/aspose.slides.mathtext/imathmatrix/deletecolumn/
---
## IMathMatrix::DeleteColumn(int32_t) method

刪除指定的欄位

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::DeleteColumn(int32_t columnIndex)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 要刪除欄位的零基索引。 |
## 備註



範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## 另請參閱

* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)