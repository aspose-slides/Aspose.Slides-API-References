---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 参考
description: 从指定的 HTML 字符串向集合添加文本。
type: docs
weight: 157
url: /zh/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) 方法

将指定的 HTML 字符串中的文本添加到集合中。

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 文本。 |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

将指定的 HTML 字符串中的文本添加到集合中。

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 文本。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 解析 URI 并获取引用对象的解析器回调对象。 |
| uri | [System::String](../../../system/string/) | 添加 HTML 文档的 URI。用于解析相对链接。 |
## 备注

指定 resolver 可能会导致漏洞。请谨慎使用。

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [String](../../../system/string/)
* 类 [ParagraphCollection](../)
* 类 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)