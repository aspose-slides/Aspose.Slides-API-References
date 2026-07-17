---
title: Contains()
second_title: Aspose.Slides C++ API 参考
description: 确定集合是否包含特定值。
type: docs
weight: 66
url: /zh/aspose.slides.mathtext/imathblockcollection/contains/
---
## IMathBlockCollection::Contains(System::SharedPtr\<IMathBlock\>) 方法

确定集合是否包含特定值。

```cpp
virtual bool Aspose::Slides::MathText::IMathBlockCollection::Contains(System::SharedPtr<IMathBlock> item)=0
```

### 参数

| Parameter | Type | Description |
| --- | --- | --- |
| item | [System::SharedPtr](../../../system/sharedptr/)\<[IMathBlock](../../imathblock/)\> | 要在集合中定位的对象。 |

### 返回值

如果在集合中找到 *item*，则返回 true；否则返回 false。

## 备注

示例：
```cpp
auto blockCollection = System::MakeObject<MathParagraph>();
auto block = System::MakeObject<MathBlock>(System::MakeObject<MathematicalText>(u"y"));
blockCollection->Add(block);
bool contains = blockCollection->Contains(block);
```

## 参见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IMathBlock](../../imathblock/)
* 类 [IMathBlockCollection](../)
* 命名空间 [Aspose::Slides::MathText](../../)
* 库 [Aspose.Slides](../../../)