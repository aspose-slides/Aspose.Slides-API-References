---
title: GetColumnAlignment()
second_title: Aspose.Slides C++ API 参考
description: 获取指定列的水平对齐方式
type: docs
weight: 235
url: /zh/aspose.slides.mathtext/imathmatrix/getcolumnalignment/
---
## IMathMatrix::GetColumnAlignment(int32_t) 方法


获取指定列的水平对齐方式

```cpp
virtual MathHorizontalAlignment Aspose::Slides::MathText::IMathMatrix::GetColumnAlignment(int32_t columnIndex)=0
```


### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| columnIndex | **int32_t** | 零基列索引 |

### 返回值

指定列的水平对齐方式
## 备注



示例： 
```cpp
auto matrix = System::MakeObject<MathMatrix>(2, 3);
auto alignment = matrix->GetColumnAlignment(0);
```

## 另请参阅

* 枚举 [MathHorizontalAlignment](../../mathhorizontalalignment/)
* 类 [IMathMatrix](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)