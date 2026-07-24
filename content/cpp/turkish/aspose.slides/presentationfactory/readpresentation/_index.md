---
title: ReadPresentation()
second_title: Aspose.Slides için C++ API Referansı
description: Varolan bir sunumu diziden okur
type: docs
weight: 40
url: /tr/aspose.slides/presentationfactory/readpresentation/
---
## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metot


Varolan bir sunumu diziden okur

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Okunacak dizi |

### Dönüş Değeri

Okunan sunum

## PresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metot


Varolan bir sunumu ek yükleme seçenekleriyle diziden okur

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Okunacak dizi |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Yükleme seçenekleri |

### Dönüş Değeri

Okunan sunum

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metot


Varolan bir sunumu akıştan okur

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Okunacak giriş akışı |

### Dönüş Değeri

Okunan sunum

## PresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metot


Varolan bir sunumu ek yükleme seçenekleriyle akıştan okur

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Okunacak giriş akışı |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Yükleme seçenekleri |

### Dönüş Değeri

Okunan sunum

## PresentationFactory::ReadPresentation(System::String) metot


Varolan bir sunumu dosyadan okur

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Dosya adı |

### Dönüş Değeri

Okunan sunum

## PresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metot


Varolan bir sunumu ek yükleme seçenekleriyle dosyadan okur

```cpp
System::SharedPtr<IPresentation> Aspose::Slides::PresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Dosya adı |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Yükleme seçenekleri |

### Dönüş Değeri

Okunan sunum

## İlgili Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [IPresentation](../../ipresentation/)
* Sınıf [PresentationFactory](../)
* Sınıf [ILoadOptions](../../iloadoptions/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [String](../../../system/string/)
* Ad alanı [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)