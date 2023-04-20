---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API Reference
description: Adds text from specified html string to the collection.
type: docs
weight: 157
url: /cpp/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) method


Adds text from specified html string to the collection.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML text. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) method


Adds text from specified html string to the collection.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML text. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Resolver callback object which resolves URIs and fetches referrenced objects. |
| uri | [System::String](../../../system/string/) | URI for adding HTML document. Used for resolving relative links. |
## Remarks



Specifying resolver can potentially introduce a vulnurability. Use with caution.
## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [ParagraphCollection](../)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)