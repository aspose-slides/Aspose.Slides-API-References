---
title: InsertColumnBefore()
second_title: Aspose.Slides for C++ API 参考
description: 在指定列之前插入一个新列。新列中的所有元素最初为 null。
type: docs
weight: 326
url: /zh/aspose.slides.mathtext/mathmatrix/insertcolumnbefore/
---
## MathMatrix::InsertColumnBefore(int32_t) 方法


在指定列之前插入一个新列。新列中的所有元素最初为 null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnBefore(int32_t columnIndex) override
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | 在其前插入新列的列索引 |
## 备注



示例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## 另请参阅

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)