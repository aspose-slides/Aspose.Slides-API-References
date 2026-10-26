---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 在集合的末尾添加一个段落。
type: docs
weight: 40
url: /zh/aspose.slides/paragraphcollection/add/
---
## ParagraphCollection::Add(System::SharedPtr\<IParagraph\>) 方法


在集合的末尾添加一个 [Paragraph](../../paragraph/)。

```cpp
void Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraph> value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 要添加到集合末尾的 [Paragraph](../../paragraph/)。 |

## ParagraphCollection::Add(System::SharedPtr\<IParagraphCollection\>) 方法


将 [ParagraphCollection](../) 内容添加到集合的末尾。

```cpp
int32_t Aspose::Slides::ParagraphCollection::Add(System::SharedPtr<IParagraphCollection> value) override
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraphCollection](../../iparagraphcollection/)\> | 要添加到集合末尾的 [ParagraphCollection](../)。 |

### 返回值

已添加 [Paragraph](../../paragraph/) 的索引，如果没有要添加的内容则返回 -1。

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [ParagraphCollection](../)
* Class [IParagraphCollection](../../iparagraphcollection/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)