---
title: ReadPresentation()
second_title: Aspose.Slides for C++ API Referansı
description: Varolan bir sunumu dizi üzerinden okur
type: docs
weight: 27
url: /tr/aspose.slides/ipresentationfactory/readpresentation/
---
## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>) metot

Varolan bir sunumu dizi üzerinden okur

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Okunacak dizi |

### Dönüş Değeri

Sunumu okur

## IPresentationFactory::ReadPresentation(System::ArrayPtr\<uint8_t\>, System::SharedPtr\<ILoadOptions\>) metot

Varolan bir sunumu dizi üzerinden ek yükleme seçenekleriyle okur

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::ArrayPtr<uint8_t> data, System::SharedPtr<ILoadOptions> options)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| data | [System::ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\> | Okunacak dizi |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Yükleme seçenekleri |

### Dönüş Değeri

Sunumu okur

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>) metot

Varolan bir sunumu akış üzerinden okur

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Okunacak giriş akışı |

### Dönüş Değeri

Sunumu okur

## IPresentationFactory::ReadPresentation(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<ILoadOptions\>) metot

Varolan bir sunumu akış üzerinden ek yükleme seçenekleriyle okur

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<ILoadOptions> options)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Okunacak giriş akışı |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Yükleme seçenekleri |

### Dönüş Değeri

Sunumu okur

## IPresentationFactory::ReadPresentation(System::String) metot

Varolan bir sunumu dosyadan okur

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Dosya adı |

### Dönüş Değeri

Sunumu okur

## IPresentationFactory::ReadPresentation(System::String, System::SharedPtr\<ILoadOptions\>) metot

Varolan bir sunumu dosyadan ek yükleme seçenekleriyle okur

```cpp
virtual System::SharedPtr<IPresentation> Aspose::Slides::IPresentationFactory::ReadPresentation(System::String file, System::SharedPtr<ILoadOptions> options)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Dosya adı |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Yükleme seçenekleri |

### Dönüş Değeri

Sunumu okur

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [IPresentation](../../ipresentation/)
* Sınıf [IPresentationFactory](../)
* Sınıf [ILoadOptions](../../iloadoptions/)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [String](../../../system/string/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)