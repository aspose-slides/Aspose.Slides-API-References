---
title: GetImage()
second_title: Aspose.Slides için C++ API Referansı
description: Özel ölçekleme ile bir görüntü nesnesi döndürür.
type: docs
weight: 105
url: /tr/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) method


Özel ölçekleme ile bir görüntü nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | **float** | Bu Küçük Resmi x ekseni yönünde ölçeklemek için kullanılacak değer. |
| scaleY | **float** | Bu Küçük Resmi y ekseni yönünde ölçeklemek için kullanılacak değer. |

### Dönüş Değeri

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() method


Gerçek boyutun %20'si kadar bir Küçük Resim Image nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Dönüş Değeri

Image object [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) method


Belirtilen boyutta bir görüntü nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Bitmap object.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) method


Belirtilen parametrelerle bir Küçük Resim tiff bitmap nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff seçenekleri. |

### Dönüş Değeri

Image object.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) method


Bir Küçük Resim Bitmap nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Render seçenekleri. |

### Dönüş Değeri

Bitmap objects.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) method


Özel ölçekleme ile bir Küçük Resim Bitmap nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Render seçenekleri. |
| scaleX | **float** | Bu Küçük Resmi x ekseni yönünde ölçeklemek için kullanılacak değer. |
| scaleY | **float** | Bu Küçük Resmi y ekseni yönünde ölçeklemek için kullanılacak değer. |

### Dönüş Değeri

Bitmap objects.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) method


Belirtilen boyutta bir Küçük Resim Bitmap nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Render seçenekleri. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Bitmap objects.

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IImage](../../iimage/)
* Sınıf [ISlide](../)
* Sınıf [Size](../../../system.drawing/size/)
* Sınıf [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Sınıf [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)