---
title: get_Count()
second_title: Aspose.Slides for C++ API 参考
description: 获取集合中实际包含的元素数量。只读 int32_t.
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathelementcollection/get_count/
---
## IMathElementCollection::get_Count() 方法

获取集合中实际包含的元素数量。只读 **int32_t**。

```cpp
virtual int32_t Aspose::Slides::MathText::IMathElementCollection::get_Count()=0
```

## 备注

示例：
```cpp
auto collection = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"x"));
int32_t count = collection->get_Count();
```

## 另请参阅

* 类 [IMathElementCollection](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)