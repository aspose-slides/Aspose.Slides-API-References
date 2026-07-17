---
title: idx_get()
second_title: Aspose.Slides C++ API 参考
description: 矩阵的元素
type: docs
weight: 209
url: /zh/aspose.slides.mathtext/mathmatrix/idx_get/
---
## MathMatrix::idx_get(int32_t, int32_t) 方法


矩阵的元素

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathMatrix::idx_get(int32_t row, int32_t column) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| row | **int32_t** | 获取项目的行的零基索引 |
| column | **int32_t** | 获取项目的列的零基索引 |

### 返回值


## 备注



示例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
matrix->idx_set(0, 0, System::MakeObject<MathematicalText>(u"item.1.1"));
```

## 参见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathElement](../../imathelement/)
* Class [MathMatrix](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)