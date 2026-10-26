---
title: InsertFromHtml()
second_title: Aspose.Slides for C++ API Referansı
description: HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.
type: docs
weight: 157
url: /tr/aspose.slides/islidecollection/insertfromhtml/
---
## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yok sayılacak. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

### Dönen Değer

Eklenen slaytlar.

## ISlideCollection::InsertFromHtml(int32_t, System::String) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |

### Dönen Değer

Eklenen slaytlar

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yok sayılacak. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

### Dönen Değer

Eklenen slaytlar.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::TextReader\>) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::TextReader> htmlReader)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlReader | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::TextReader](../../../system.io/textreader/)\> | HTML dosyasının kaynağı olarak kullanılacak TextReader nesnesi. |

### Dönen Değer

Eklenen slaytlar

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yok sayılacak. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |

### Dönen Değer

Eklenen slaytlar.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |

### Dönen Değer

Eklenen slaytlar

## ISlideCollection::InsertFromHtml(int32_t, System::String, bool) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, bool useSlideWithIndexAsStart)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |
| useSlideWithIndexAsStart | **bool** | Bu bayrak eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen dizindeki slayttan mı. **true** ise veri ekleme, belirtilen dizindeki slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir. |

### Dönen Değer

Eklenen slaytlar

## ISlideCollection::InsertFromHtml(int32_t, System::String, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::String htmlText, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlText | [System::String](../../../system/string/) | Eklenecek HTML. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yok sayılacak. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |
| useSlideWithIndexAsStart | **bool** | Bu bayrak eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen dizindeki slayttan mı. **true** ise veri ekleme, belirtilen dizindeki slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir. |

### Dönen Değer

Eklenen slaytlar.

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, bool) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, bool useSlideWithIndexAsStart)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |
| useSlideWithIndexAsStart | **bool** | Bu bayrak eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen dizindeki slayttan mı. **true** ise veri ekleme, belirtilen dizindeki slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir. |

### Dönen Değer

Eklenen slaytlar

## ISlideCollection::InsertFromHtml(int32_t, System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Import::IExternalResourceResolver\>, System::String, bool) yöntemi

HTML metninden slaytlar oluşturur ve belirtilen konuma koleksiyona ekler.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::InsertFromHtml(int32_t index, System::SharedPtr<System::IO::Stream> htmlStream, System::SharedPtr<Import::IExternalResourceResolver> resolver, System::String uri, bool useSlideWithIndexAsStart)=0
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | **int32_t** | Eklenecek konum. |
| htmlStream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | HTML dosyasının kaynağı olarak kullanılacak Stream nesnesi. |
| resolver | [System::SharedPtr](../../../system/sharedptr/)\<[Import::IExternalResourceResolver](../../../aspose.slides.import/iexternalresourceresolver/)\> | Harici nesneleri getirmek için kullanılan geri çağırma nesnesi. Bu parametre null ise tüm harici nesneler yok sayılacak. |
| uri | [System::String](../../../system/string/) | Belirtilen HTML'nin URI'si. Göreceli bağlantıları çözmek için kullanılır. |
| useSlideWithIndexAsStart | **bool** | Bu bayrak eklemeye nasıl başlanacağını belirler: yeni bir slayttan mı yoksa belirtilen dizindeki slayttan mı. **true** ise veri ekleme, belirtilen dizindeki slaytın boş alanından başlar. **false** ise veri oluşturulan slaytlara eklenir. |

### Dönen Değer

Eklenen slaytlar.

## Ayrıca Bakınız

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