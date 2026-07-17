---
title: DeleteColumn()
second_title: Aspose.Slides for C++ API 参考
description: 删除指定的列
type: docs
weight: 352
url: /zh/aspose.slides.mathtext/mathmatrix/deletecolumn/
---
## MathMatrix::DeleteColumn(int32_t) 方法

删除指定的列

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteColumn(int32_t columnIndex) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| columnIndex | **int32_t** | 要删除的列的零基索引。 |
## 备注

示例: 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteColumn(0);
```

## 另见

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)