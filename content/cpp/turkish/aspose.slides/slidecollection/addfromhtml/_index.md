---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API Referansı
description: HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.
type: docs
weight: 196
url: /tr/aspose.slides/slidecollection/addfromhtml/
---
## SlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metot


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin bir URI'si. Göreli bağlantıları çözmek için kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

## SlideCollection::AddFromHtml(System::String) metot


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::String htmlText) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |

### Dönüş Değeri

Eklenen slaytlar

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metot


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Bir HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin bir URI'si. Göreli bağlantıları çözmek için kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) metot


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | Bir HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |

### Dönüş Değeri

Eklenen slaytlar

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metot


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Bir HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yoksayılır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin bir URI'si. Göreli bağlantıları çözmek için kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

## SlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) metot


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Bir HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |

### Dönüş Değeri

Eklenen slaytlar
## Açıklamalar




```cpp
// Presentation sınıfının bir örneğini oluştur.
auto presentation = System::MakeObject<Presentation>();

{
    auto htmlStream = System::IO::File::OpenRead(u"page.html");

    // AddFromHtml metodunu çağır ve HTML dosyasını geçir.
    presentation->get_Slides()->AddFromHtml(htmlStream);
}

// Dosyayı PowerPoint belgesi olarak kaydetmek için Save metodunu kullan.
presentation->Save(u"MyPresentation.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlide](../../islide/)
* Sınıf [String](../../../system/string/)
* Sınıf [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Sınıf [SlideCollection](../)
* Sınıf [TextReader](../../../system.io/textreader/)
* Sınıf [Stream](../../../system.io/stream/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)