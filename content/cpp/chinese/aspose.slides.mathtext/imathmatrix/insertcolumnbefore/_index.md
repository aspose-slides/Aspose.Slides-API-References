---
title: InsertColumnBefore()
second_title: Aspose.Slides C++ API 参考
description: 在指定列之前插入一个新列，新的列中的所有元素最初为 null。
type: docs
weight: 313
url: /zh/aspose.slides.mathtext/imathmatrix/insertcolumnbefore/
---
## IMathMatrix::InsertColumnBefore(int32_t) 方法

在指定列之前插入一个新列。新列中的所有元素最初均为 null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertColumnBefore(int32_t columnIndex)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | **int32_t** | 在其之前插入新列的列索引 |
## 备注

示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertColumnBefore(0);
```

## 另见

* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)