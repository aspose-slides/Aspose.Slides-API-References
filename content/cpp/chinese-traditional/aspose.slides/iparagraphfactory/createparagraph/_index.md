---
title: CreateParagraph()
second_title: Aspose.Slides for C++ API 參考
description: 建立一個新的空白段落。
type: docs
weight: 1
url: /zh-hant/aspose.slides/iparagraphfactory/createparagraph/
---
## IParagraphFactory::CreateParagraph() 方法


建立一個新的空白段落。

```cpp
virtual System::SharedPtr<IParagraph> Aspose::Slides::IParagraphFactory::CreateParagraph()=0
```


### 傳回值

[Paragraph](../../paragraph/).

## IParagraphFactory::CreateParagraph(System::SharedPtr\<IParagraph\>) 方法


使用指定的段落資料建立新段落。

```cpp
virtual System::SharedPtr<IParagraph> Aspose::Slides::IParagraphFactory::CreateParagraph(System::SharedPtr<IParagraph> paragraph)=0
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| paragraph | [System::SharedPtr](../../../system/sharedptr/)\<[IParagraph](../../iparagraph/)\> | 用於使用資料的段落。 |

### 傳回值

[Paragraph](../../paragraph/).

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IParagraph](../../iparagraph/)
* Class [IParagraphFactory](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)