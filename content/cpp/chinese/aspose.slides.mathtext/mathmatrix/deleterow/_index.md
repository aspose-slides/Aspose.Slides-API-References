---
title: DeleteRow()
second_title: Aspose.Slides C++ API 参考
description: 删除指定的行
type: docs
weight: 313
url: /zh/aspose.slides.mathtext/mathmatrix/deleterow/
---
## MathMatrix::DeleteRow(int32_t) 方法


删除指定的行

```cpp
void Aspose::Slides::MathText::MathMatrix::DeleteRow(int32_t rowIndex) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| rowIndex | **int32_t** | 要删除的行的零基索引。 |
## 备注



示例:
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->DeleteRow(0);
```

## 另请参见

* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)