---
title: SetColumnAlignment()
second_title: Aspose.Slides for C++ API 參考文件
description: 設定指定欄位的水平對齊方式
type: docs
weight: 248
url: /zh-hant/aspose.slides.mathtext/imathmatrix/setcolumnalignment/
---
## IMathMatrix::SetColumnAlignment(int32_t, MathHorizontalAlignment) 方法


設定指定欄位的水平對齊方式

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::SetColumnAlignment(int32_t columnIndex, MathHorizontalAlignment val)=0
```


### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| columnIndex | **int32_t** | 從零開始的欄位索引 |
| val | [MathHorizontalAlignment](../../mathhorizontalalignment/) | 指定欄位水平對齊方式的新值 |
## 備註



範例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->SetColumnAlignment(0, MathHorizontalAlignment::Left);
```

## 另見

* 列舉 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)