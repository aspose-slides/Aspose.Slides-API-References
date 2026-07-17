---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API 参考
description: 在指定行之后插入一行新行。新行中的所有元素初始为 null。
type: docs
weight: 300
url: /zh/aspose.slides.mathtext/mathmatrix/insertrowafter/
---
## MathMatrix::InsertRowAfter(int32_t) 方法

在指定行之后插入一行新行。新行中的所有元素初始为 null。

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowAfter(int32_t rowIndex) override
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| rowIndex | **int32_t** | 在其后插入新行的行索引 |
## 备注



示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## 另见

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)