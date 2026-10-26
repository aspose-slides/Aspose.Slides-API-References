---
title: idx_set()
second_title: Aspose.Slides C++ API 参考
description: 矩阵的元素
type: docs
weight: 222
url: /zh/aspose.slides.mathtext/mathmatrix/idx_set/
---
## MathMatrix::idx_set(int32_t, int32_t, System::SharedPtr\<IMathElement\>) 方法

矩阵的元素

```cpp
void Aspose::Slides::MathText::MathMatrix::idx_set(int32_t row, int32_t column, System::SharedPtr<IMathElement> value) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| row | **int32_t** | 获取项的行的零基索引 |
| column | **int32_t** | 获取项的列的零基索引 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IMathElement](../../imathelement/)\> |  |

## 备注



示例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## 另请参阅

* 类型别名 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)