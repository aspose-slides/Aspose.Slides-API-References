---
title: idx_get()
second_title: Aspose.Slides for C++ API 參考
description: 矩陣的元素
type: docs
weight: 209
url: /zh-hant/aspose.slides.mathtext/imathmatrix/idx_get/
---
## IMathMatrix::idx_get(int32_t, int32_t) 方法


矩陣的元素

```cpp
virtual System::SharedPtr<IMathElement> Aspose::Slides::MathText::IMathMatrix::idx_get(int32_t row, int32_t column)=0
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| row | **int32_t** | 零基索引的列，用於取得項目 |
| column | **int32_t** | 零基索引的欄，用於取得項目 |

### 回傳值


## 備註



範例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## See Also

* 型別別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IMathElement](../../imathelement/)
* 類別 [IMathMatrix](../)
* 命名空間 [Aspose::Slides::MathText](../../)
* 函式庫 [Aspose.Slides](../../../)