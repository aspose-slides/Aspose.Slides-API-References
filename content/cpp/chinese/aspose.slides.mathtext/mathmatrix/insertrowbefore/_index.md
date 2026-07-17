---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API 参考
description: 在指定行之前插入一行新行。新行中的所有元素最初为 null。
type: docs
weight: 287
url: /zh/aspose.slides.mathtext/mathmatrix/insertrowbefore/
---
## MathMatrix::InsertRowBefore(int32_t) 方法

在指定行之前插入一行新行。新行中的所有元素最初为 null.

```cpp
void Aspose::Slides::MathText::MathMatrix::InsertRowBefore(int32_t rowIndex) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | **int32_t** | 要在其之前插入新行的行索引 |
## 备注



示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## 另请参见

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)