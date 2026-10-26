---
title: Insert()
second_title: Aspose.Slides C++ API 参考
description: 在指定索引处将 Paragraph 插入到集合中。
type: docs
weight: 40
url: /zh/aspose.slides/iparagraphcollection/insert/
---
## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraph\>) 方法

在指定索引处将 [Paragraph](../../paragraph/) 插入到集合中。

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraph> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 在应插入 [Paragraph](../../paragraph/) 的零基索引。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 要插入的 [Paragraph](../../paragraph/)。 |

## IParagraphCollection::Insert(int32_t, System::SharedPtr\<IParagraphCollection\>) 方法

在指定索引处将 [ParagraphCollection](../../paragraphcollection/) 的内容插入到集合中。

```cpp
virtual void Aspose::Slides::IParagraphCollection::Insert(int32_t index, System::SharedPtr<IParagraphCollection> value)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| index | **int32_t** | 在应插入段落的零基索引。 |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../)\> | 要插入的段落。 |

## 另请参阅

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IParagraph](../../iparagraph/)
* 类 [IParagraphCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)