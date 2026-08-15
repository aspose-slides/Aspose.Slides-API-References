---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考文件
description: 矩陣的元素
type: docs
weight: 209
url: /zh-hant/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) 方法

矩陣的元素

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| row | **int32_t** | row 的零基索引，用於取得項目 |
| column | **int32_t** | column 的零基索引，用於取得項目 |

### 回傳值


## 備註



範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)