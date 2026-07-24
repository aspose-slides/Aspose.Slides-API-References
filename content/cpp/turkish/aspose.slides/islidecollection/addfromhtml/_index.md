---
title: AddFromHtml()
second_title: Aspose.Slides for C++ API Referansı
description: HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.
type: docs
weight: 144
url: /tr/aspose.slides/islidecollection/addfromhtml/
---
## ISlideCollection::AddFromHtml(System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) yöntem


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Dış nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

## ISlideCollection::AddFromHtml(System::String) yöntem


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::String htmlText)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |

### Dönüş Değeri

Eklenen slaytlar

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) yöntem


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Dış nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::TextReader\>) yönt

HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::TextReader> htmlReader)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |

### Dönüş Değeri

Eklenen slaytlar

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) yöntem


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Dış nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm dış nesneler yok sayılır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

## ISlideCollection::AddFromHtml(System::SharedPtr\<System::IO::Stream\>) yöntem


HTML metninden slaytlar oluşturur ve bunları koleksiyonun sonuna ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::AddFromHtml(System::SharedPtr<System::IO::Stream> htmlStream)=0
```


### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |

### Dönüş Değeri

Eklenen slaytlar

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlide](../../islide/)
* Sınıf [String](../../../system/string/)
* Sınıf [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Sınıf [ISlideCollection](../)
* Sınıf [TextReader](../../../system.io/textreader/)
* Sınıf [Stream](../../../system.io/stream/)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)