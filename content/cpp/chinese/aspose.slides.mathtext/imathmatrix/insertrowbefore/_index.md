---
title: InsertRowBefore()
second_title: Aspose.Slides for C++ API 参考
description: 在指定的行之前插入新行，新行中的所有元素最初为 null。
type: docs
weight: 274
url: /zh/aspose.slides.mathtext/imathmatrix/insertrowbefore/
---
## IMathMatrix::InsertRowBefore(int32_t) 方法

在指定的行之前插入新行。新行中的所有元素最初为 null.

```cpp
virtual void Aspose::Slides::MathText::IMathMatrix::InsertRowBefore(int32_t rowIndex)=0
```

### 参数

| 参数 | 类型 | 说明 |
| --- | --- | --- |
| rowIndex | **int32_t** | 在其之前插入新行的行索引 |
## 备注



示例：
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->InsertRowBefore(1);
```

## 另请参见

* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)