---
title: SetColumnAlignment()
second_title: Aspose.Slides C++ API 參考
description: 設定指定欄位的水平對齊方式
type: docs
weight: 261
url: /zh-hant/aspose.slides.mathtext/mathmatrix/setcolumnalignment/
---
## MathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) 方法

設定指定欄位的水平對齊方式

```cpp
void Aspose::Slides::MathText::MathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| columnIndex | **int32_t** | 零基欄索引 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 指定欄位的水平對齊新值 |
## 備註

範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## 另請參閱

* 列舉 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 類別 [MathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)