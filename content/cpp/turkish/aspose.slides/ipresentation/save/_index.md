---
title: Save()
second_title: Aspose.Slides C++ API Referansı
description: Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.
type: docs
weight: 404
url: /tr/aspose.slides/ipresentation/save/
---
## IPresentation::Save(System::String, Export::SaveFormat) metot


Bir sunumun tüm slaytlarını belirtilen formatta bir dosyaya kaydeder.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Oluşturulan dosyanın yolu. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Dışa aktarılan verinin formatı. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat) metot


Bir sunumun tüm slaytlarını belirtilen formatta bir akışa kaydeder.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Çıktı akışı. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Dışa aktarılan verinin formatı. |

## IPresentation::Save(System::String, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metot


Bir sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir dosyaya kaydeder.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Oluşturulan dosyanın yolu. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Dışa aktarılan verinin formatı. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Ek format seçenekleri. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metot


Bir sunumun tüm slaytlarını belirtilen formatta ve ek seçeneklerle bir akışa kaydeder.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Çıktı akışı. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Dışa aktarılan verinin formatı. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Ek format seçenekleri. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat) metot


Belirtilen slaytları belirtilen formatta bir dosyaya kaydeder.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Oluşturulan dosyanın yolu. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1’den başlayan slayt konumlarını içeren dizi. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Dışa aktarılan verinin formatı. |

## IPresentation::Save(System::String, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metot


Belirtilen slaytları belirtilen formatta bir dosyaya kaydeder.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::String fname, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| fname | [System::String](../../../system/string/) | Oluşturulan dosyanın yolu. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1’den başlayan slayt konumlarını içeren dizi. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Dışa aktarılan verinin formatı. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Ek format seçenekleri. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat) metot


Belirtilen slaytları belirtilen formatta bir akışa kaydeder.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Çıktı akışı. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1’den başlayan slayt konumlarını içeren dizi. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Dışa aktarılan verinin formatı. |

## IPresentation::Save(System::SharedPtr\<System::IO::Stream\>, System::ArrayPtr\<int32_t\>, Export::SaveFormat, System::SharedPtr\<Export::ISaveOptions\>) metot


Belirtilen slaytları belirtilen formatta bir akışa kaydeder.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<System::IO::Stream> stream, System::ArrayPtr<int32_t> slides, Export::SaveFormat format, System::SharedPtr<Export::ISaveOptions> options)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Çıktı akışı. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1’den başlayan slayt konumlarını içeren dizi. |
| format | [Export::SaveFormat](../../../aspose.slides.export/saveformat/) | Dışa aktarılan verinin formatı. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISaveOptions](../../../aspose.slides.export/isaveoptions/)\> | Ek format seçenekleri. |

## IPresentation::Save(System::SharedPtr\<Export::Xaml::IXamlOptions\>) metot


Bir sunumun tüm slaytlarını XAML biçiminde dosyalar kümesine kaydeder.

```cpp
virtual void Aspose::Slides::IPresentation::Save(System::SharedPtr<Export::Xaml::IXamlOptions> options)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::Xaml::IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)\> | XAML format seçenekleri. |
## Açıklamalar



```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

SharedPtr<IXamlOptions> options = System::MakeObject<XamlOptions>();
options->set_ExportHiddenSlides(true);

pres->Save(options);
```




## Diğer Bağlantılar

* Enum [SaveFormat](../../../aspose.slides.export/saveformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Sınıf [String](../../../system/string/)
* Sınıf [IPresentation](../)
* Sınıf [Stream](../../../system.io/stream/)
* Sınıf [ISaveOptions](../../../aspose.slides.export/isaveoptions/)
* Sınıf [IXamlOptions](../../../aspose.slides.export.xaml/ixamloptions/)
* İsim Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)