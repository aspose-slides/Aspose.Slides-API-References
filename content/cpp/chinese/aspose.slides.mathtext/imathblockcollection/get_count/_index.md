---
title: get_Count()
second_title: Aspose.Slides for C++ API 参考
description: 获取集合中实际包含的元素数量。只读 int32_t。
type: docs
weight: 1
url: /zh/aspose.slides.mathtext/imathblockcollection/get_count/
---
## IMathBlockCollection::get_Count() 方法

获取集合中实际包含的元素数量。只读 **int32_t**。

```cpp
virtual int32_t Aspose::Slides::MathText::IMathBlockCollection::get_Count()=0
```

## 备注

示例： 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
int32_t blocksCount = blockCollection->get_Count();
```

## 另请参见

* 类 [IMathBlockCollection](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)