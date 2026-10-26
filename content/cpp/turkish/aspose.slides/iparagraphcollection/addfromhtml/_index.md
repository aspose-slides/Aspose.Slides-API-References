---
title: AddFromHtml()
second_title: Aspose.Slides C++ API Referansı
description: Belirtilen html dizesinden metni koleksiyona ekler.
type: docs
weight: 92
url: /tr/aspose.slides/iparagraphcollection/addfromhtml/
---
## IParagraphCollection::AddFromHtml(System::String) yöntemi


Belirtilen html dizesinden metni koleksiyona ekler.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML metni. |

## IParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) yöntemi


Belirtilen html dizesinden metni koleksiyona ekler.

```cpp
virtual void Aspose::Slides::IParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML metni. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | URI'leri çözen ve başvurulan nesneleri getiren çözümleyici geri çağırma nesnesi. |
| uri | [System::String](../../../system/string/) | HTML belgesi eklemek için URI. Göreceli bağlantıların çözülmesinde kullanılır. |
## Açıklamalar



Çözümleyici belirtmek potansiyel bir güvenlik açığına yol açabilir. Dikkatle kullanın.
## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [String](../../../system/string/)
* Class [IParagraphCollection](../)
* Class [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Namespace [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)