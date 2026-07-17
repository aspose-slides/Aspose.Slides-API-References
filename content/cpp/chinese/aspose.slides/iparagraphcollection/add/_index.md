---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 将 Paragraph 添加到集合的末尾。
type: docs
weight: 27
url: /zh/aspose.slides/iparagraphcollection/add/
---
## IParagraphCollection::Add(System::SharedPtr\<IParagraph\>) 方法

将一个[Paragraph](../../paragraph/)添加到集合的末尾。

```cpp
virtual void Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraph> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 要添加到集合末尾的[Paragraph](../../paragraph/)。 |

## IParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) 方法

将[ParagraphCollection](../../paragraphcollection/)的内容添加到集合的末尾。

```cpp
virtual int32_t Aspose::Slides::IParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | 要添加到集合末尾的[ParagraphCollection](../../paragraphcollection/)。 |

### 返回值

已添加[Paragraph](../../paragraph/)的索引，如果没有任何内容可添加则为 -1。

## 另请参阅

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IParagraph](../../iparagraph/)
* 类 [IParagraphCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)