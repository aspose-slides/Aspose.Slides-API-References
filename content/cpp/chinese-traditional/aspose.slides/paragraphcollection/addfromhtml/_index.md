---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的 HTML 字串中的文字新增至集合。
type: docs
weight: 157
url: /zh-hant/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) 方法

將指定的 HTML 字串中的文字新增至集合。

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 文字。 |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

將指定的 HTML 字串中的文字新增至集合。

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 文字。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 解析 URI 並取得參照物件的解析器回呼物件。 |
| uri | [System::String](../../../system/string/) | 用於加入 HTML 文件的 URI。用於解析相對連結。 |
## 備註

指定解析器可能會導致安全漏洞。請謹慎使用。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ParagraphCollection](../)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)