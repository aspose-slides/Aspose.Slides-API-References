---
title: InsertRowAfter()
second_title: Aspose.Slides for C++ API 参考
description: 在指定的行之后插入新行，新的行中的所有元素最初均为 null。
type: docs
weight: 287
url: /zh/aspose.slides.mathtext/imathmatrix/insertrowafter/
---
## IMathMatrix::InsertRowAfter(int32_t) 方法

在指定行之后插入一行新行，新的行中的所有元素最初均为 null。

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowAfter(int32_t rowIndex)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | **int32_t** | 在其后插入新行的行索引 |
## 备注



示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowAfter(1);
```

## 另请参见

* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)