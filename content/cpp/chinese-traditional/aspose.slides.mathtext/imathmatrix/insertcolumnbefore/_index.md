---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API 參考文件
description: 在指定的列之前插入新列。新列中的所有元素最初皆為 null。
type: docs
weight: 313
url: /zh-hant/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) 方法

在指定的列之前插入一個新列。新列中的所有元素最初皆為 null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```

### 參數

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | 在插入新列之前的列索引 |

## 備註

範例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## 另見

* Class [IMathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)