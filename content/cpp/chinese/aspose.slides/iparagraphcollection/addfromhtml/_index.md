---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 参考
description: 将指定的 html 字符串中的文本添加到集合中。
type: docs
weight: 92
url: /zh/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) 方法


将指定的 html 字符串中的文本添加到集合中。

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 文本。 |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法


将指定的 html 字符串中的文本添加到集合中。

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 文本。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 解析器回调对象，用于解析 URI 并获取引用的对象。 |
| uri | [System::String](../../../system/string/) | 用于添加 HTML 文档的 URI。用于解析相对链接。 |
## 备注



指定解析器可能会导致漏洞。请谨慎使用。
## 另见

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IParagraphCollection](../)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)