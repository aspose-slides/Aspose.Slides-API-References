---
title: GetImages()
second_title: Aspose.Slides for C++ API Referansı
description: Bir sunumun tüm slaytları için Image nesnelerini döndürür.
type: docs
weight: 456
url: /tr/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) yöntemi


Bir sunumun tüm slaytları için Image nesnelerini döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff seçenekleri. |

### Dönüş Değeri

Image nesneleri.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) yöntemi


Belirtilen slaytlar için bir sunumun Thumbnail Image nesnelerini döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff seçenekleri. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1’den başlayan slayt konumlarını içeren dizi. |

### Dönüş Değeri

Image nesneleri.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) yöntemi


Özel ölçekleme ile bir sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff seçenekleri. |
| scaleX | **float** | Bu Thumbnail’i x ekseninde ölçeklemek için kullanılacak değer. |
| scaleY | **float** | Bu Thumbnail’i y ekseninde ölçeklemek için kullanılacak değer. |

### Dönüş Değeri

Image nesneleri.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) yöntemi


Özel ölçekleme ile bir sunumun belirtilen slaytları için Thumbnail Image nesnelerini döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff seçenekleri. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1’den başlayan slayt konumlarını içeren dizi. |
| scaleX | **float** | Bu Thumbnail’i x ekseninde ölçeklemek için kullanılacak değer. |
| scaleY | **float** | Bu Thumbnail’i y ekseninde ölçeklemek için kullanılacak değer. |

### Dönüş Değeri

Image nesneleri.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) yöntemi


Belirtilen boyutta bir sunumun tüm slaytları için Thumbnail Image nesnelerini döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff seçenekleri. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Image nesneleri.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) yöntemi


Belirtilen boyutta bir sunumun belirtilen slaytları için Thumbnail Image nesnelerini döndürür.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Tiff seçenekleri. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | 1’den başlayan slayt konumlarını içeren dizi. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Image nesneleri.

## İlgili

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [Presentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)