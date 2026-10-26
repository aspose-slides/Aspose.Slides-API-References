---
title: CreateParagraph()
second_title: Aspose.Slides C++ API 参考
description: 创建一个新的空段落。
type: docs
weight: 1
url: /zh/aspose.slides/iparagraphfactory/createparagraph/
---
## IParagraphFactory::CreateParagraph() 方法

创建一个新的空段落。

```cpp
virtual System::SharedPtr<IParagraph> Aspose::Slides::IParagraphFactory::CreateParagraph()=0
```

### 返回值

[Paragraph](../../paragraph/).

## IParagraphFactory::CreateParagraph(System::SharedPtr\<IParagraph\>) 方法

使用指定的段落数据创建一个新的段落。

```cpp
virtual System::SharedPtr<IParagraph> Aspose::Slides::IParagraphFactory::CreateParagraph(System::SharedPtr<IParagraph> paragraph)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 用于使用数据的段落。 |

### 返回值

[Paragraph](../../paragraph/).

## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* 类 [IParagraph](../../iparagraph/)
* 类 [IParagraphFactory](../)
* 命名空间 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)