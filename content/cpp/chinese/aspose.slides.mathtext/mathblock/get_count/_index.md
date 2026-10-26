---
title: get_Count()
second_title: Aspose.Slides for C++ API 参考
description: 获取集合中实际包含的子数学元素的数量。只读 int32_t。
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/mathblock/get_count/
---
## MathBlock::get_Count() 方法

获取集合中实际包含的子数学元素的数量。只读 **int32_t**.

```cpp
int32_t Aspose::Slides::MathText::MathBlock::get_Count() override
```

## 备注

示例：
```cpp
auto mathBlock = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = mathBlock->get_Count();
```

## 另见

* 类 [MathBlock](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)