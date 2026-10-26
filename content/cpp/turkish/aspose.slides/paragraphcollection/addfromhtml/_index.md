---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen HTML dizesinden metni koleksiyona ekler.
type: docs
weight: 157
url: /tr/aspose.slides/paragraphcollection/addfromhtml/
---
## ParagraphCollection::AddFromHtml(System::String) metot

Belirtilen HTML dizesinden metni koleksiyona ekler.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML metni. |

## ParagraphCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metot

Belirtilen HTML dizesinden metni koleksiyona ekler.

```cpp
void Aspose::Slides::ParagraphCollection::AddFromHtml(System::String text, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| text | [System::String](../../../system/string/) | HTML metni. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | URI'leri çözen ve başvurulan nesneleri getiren çözücü geri çağırma nesnesi. |
| uri | [System::String](../../../system/string/) | HTML belgesini eklemek için URI. Göreli bağlantıların çözülmesinde kullanılır. |
## Açıklamalar

Çözücü belirtmek, potansiyel olarak bir güvenlik açığı oluşturabilir. Dikkatli kullanın.
## Ayrıca Bakınız

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [ParagraphCollection](../)
* Sınıf [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)