---
title: InsertFromHtml()
second_title: Aspose.Slides için C++ API Referansı
description: HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.
type: docs
weight: 209
url: /tr/aspose.slides/slidecollection/insertfromhtml/
---
## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler görmezleme alınır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreli bağlantıları çözmek için kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

## SlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler görmezleme alınır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreli bağlantıları çözmek için kullanılır. |
| useSlideWithIndexAsStart | **bool** | Bu bayrak, eklemeye yeni bir slayt üzerinden mi yoksa belirtilen indekse sahip slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indekse sahip slayttaki boş bir alandan başlar. **false** ise veri, oluşturulan slaytlara eklenir. |

### Dönüş Değeri

Eklenen slaytlar.

## SlideCollection::InsertFromHtml(int32_t, System::String) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |

### Dönüş Değeri

Eklenen slaytlar

## SlideCollection::InsertFromHtml(int32_t, System::String, bool) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |
| useSlideWithIndexAsStart | **bool** | Bu bayrak, eklemeye yeni bir slayt üzerinden mi yoksa belirtilen indekse sahip slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indekse sahip slayttaki boş bir alandan başlar. **false** ise veri, oluşturulan slaytlara eklenir. |

### Dönüş Değeri

Eklenen slaytlar

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler görmezleme alınır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreli bağlantıları çözmek için kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |

### Dönüş Değeri

Eklenen slaytlar

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler görmezleme alınır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreli bağlantıları çözmek için kullanılır. |

### Dönüş Değeri

Eklenen slaytlar.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri almak için kullanılan bir geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler görmezleme alınır. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreli bağlantıları çözmek için kullanılır. |
| useSlideWithIndexAsStart | **bool** | Bu bayrak, eklemeye yeni bir slayt üzerinden mi yoksa belirtilen indekse sahip slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indekse sahip slayttaki boş bir alandan başlar. **false** ise veri, oluşturulan slaytlara eklenir. |

### Dönüş Değeri

Eklenen slaytlar.

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |

### Dönüş Değeri

Eklenen slaytlar

## SlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) metod


HTML metninden slaytlar oluşturur ve belirtilen konumda koleksiyona ekler.

```cpp
System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::SlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |
| useSlideWithIndexAsStart | **bool** | Bu bayrak, eklemeye yeni bir slayt üzerinden mi yoksa belirtilen indekse sahip slayttan mı başlanacağını belirler. **true** ise veri ekleme, belirtilen indekse sahip slayttaki boş bir alandan başlar. **false** ise veri, oluşturulan slaytlara eklenir. |

### Dönüş Değeri

Eklenen slaytlar

## Ayrıca Bakın

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISlide](../../islide/)
* Sınıf [String](../../../system/string/)
* Sınıf [IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)
* Sınıf [SlideCollection](../)
* Sınıf [TextReader](../../../system.io/textreader/)
* Sınıf [Stream](../../../system.io/stream/)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)