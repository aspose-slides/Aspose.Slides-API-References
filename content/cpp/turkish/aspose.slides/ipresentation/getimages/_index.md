---
title: GetImages()
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumun tüm slaytları için Thumbnail Image nesneleri döndürür.
type: docs
weight: 417
url: /tr/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) metot


Bir sunumun tüm slaytları için Thumbnail Image nesneleri döndürür.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderleme seçenekleri. |

### Dönüş Değeri

Bitmap nesneleri.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) metot


Belirtilen slaytlar için Thumbnail Bitmap nesneleri döndürür.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderleme seçenekleri. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1'den başlayan slayt konumlarını içeren dizi. |

### Dönüş Değeri

Bitmap nesneleri.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metot


Özel ölçeklendirme ile bir sunumun tüm slaytları için Thumbnail Image nesneleri döndürür.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderleme seçenekleri. |
| scaleX | **float** | Bu Thumbnail'in x ekseninde ölçeklenecek değeri. |
| scaleY | **float** | Bu Thumbnail'in y ekseninde ölçeklenecek değeri. |

### Dönüş Değeri

Bitmap nesneleri.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) metot


Özel ölçeklendirme ile belirtilen slaytlar için Thumbnail Image nesneleri döndürür.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderleme seçenekleri. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1'den başlayan slayt konumlarını içeren dizi. |
| scaleX | **float** | Bu Thumbnail'in x ekseninde ölçeklenecek değeri. |
| scaleY | **float** | Bu Thumbnail'in y ekseninde ölçeklenecek değeri. |

### Dönüş Değeri

Bitmap nesneleri.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metot


Belirtilen boyutta bir sunumun tüm slaytları için Thumbnail Image nesneleri döndürür.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderleme seçenekleri. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Bitmap nesneleri.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) metot


Belirtilen boyutta, belirtilen slaytlar için Thumbnail Image nesneleri döndürür.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```


### Parametreler

| Parameter | Type | Description |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderleme seçenekleri. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1'den başlayan slayt konumlarını içeren dizi. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Bitmap nesneleri.

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)