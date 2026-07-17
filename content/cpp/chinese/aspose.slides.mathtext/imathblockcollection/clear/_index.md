---
title: Clear()
second_title: Aspose.Slides for C++ API 参考
description: 从集合中移除所有元素。
type: docs
weight: 118
url: /zh/aspose.slides.mathtext/imathblockcollection/clear/
---
## IMathBlockCollection::Clear() 方法

从集合中移除所有元素。

```cpp
virtual void Aspose::Slides::MathText::IMathBlockCollection::Clear()=0
```

## 备注

示例:
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block1")));
blockCollection->Add(System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"block2")));
blockCollection->Clear();
```

## 另请参阅

* 类 [IMathBlockCollection](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)