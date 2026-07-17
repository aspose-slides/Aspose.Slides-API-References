---
title: idx_get()
second_title: Aspose.Slides for C++ API 参考
description: 在指定索引处获取 IMathElement。
type: docs
weight: 27
url: /zh/aspose.slides.mathtext/mathblock/idx_get/
---
## MathBlock::idx_get(int32_t) 方法

在指定索引获取 [IMathElement](../../imathelement/)。

```cpp
System::SharedPtr<IMathElement> Aspose::Slides::MathText::MathBlock::idx_get(int32_t index) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 项目的从零开始的索引 |

### 返回值

数学元素。

## 备注



示例： 
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
auto firstElem = mathBlock->idx_get(0);
```

## 另请参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathElement](../../imathelement/)
* 类 [MathBlock](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)