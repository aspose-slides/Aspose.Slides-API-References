---
title: InsertColumnAfter()
second_title: Aspose.Slides for C++ API 参考
description: 在指定列之后插入一个新列，新的列中的所有元素最初为 null。
type: docs
weight: 339
url: /zh/aspose.slides.mathtext/mathmatrix/insertcolumnafter/
---
## MathMatrix::InsertColumnAfter(int32_t) 方法


在指定列之后插入一个新列。新列中的所有元素最初为 null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertColumnAfter(int32_t columnIndex) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | **int32_t** | 在其后插入新列的列索引 |
## 备注



示例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnAfter(0);
```

## 另请参阅

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)