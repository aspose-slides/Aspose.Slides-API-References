---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的 HTML 文字字串新增至集合。
type: docs
weight: 92
url: /zh-hant/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) 方法

將指定的 HTML 文字字串新增至集合。

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 文字。 |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) 方法

將指定的 HTML 文字字串新增至集合。

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML 文字。 |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | 解析 URI 並取得參考物件的回呼物件。 |
| uri | [System::String](../../../system/string/) | 用於新增 HTML 文件的 URI。用於解析相對連結。 |

## 備註

指定 resolver 可能會潛在引入漏洞。請謹慎使用。

## 另見

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [String](../../../system/string/)
* 類別 [IParagraphCollection](../)
* 類別 [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)