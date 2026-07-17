---
title: Remove()
second_title: Aspose.Slides for C++ API 参考
description: 从集合中删除特定对象的第一次出现/>。
type: docs
weight: 40
url: /zh/aspose.slides.mathtext/imathblockcollection/remove/
---
## IMathBlockCollection::Remove(System::SharedPtr\<IMathBlock\>) method

从集合中移除指定对象的第一次出现/>。

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Remove(System::SharedPtr<IMathBlock> item)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要从集合中移除的对象。 |

### 返回值

true if *item*  was successfully removed from the collection; otherwise, false. This method also returns false if *item*  is not found in the original collection/>.

## 备注


示例： 
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
blockCollection->Remove(block);
```

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMathBlock](../../imathblock/)
* Class [IMathBlockCollection](../)
* Namespace [Aspose::Slides::MathText](../../)
* Library [Aspose.Slides](../../../)