---
title: GetImage()
second_title: Aspose.Slides for C++ API Referansı
description: Özel ölçeklendirme ile bir görüntü nesnesi döndürür.
type: docs
weight: 105
url: /tr/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) metod

Özel ölçeklendirme ile bir görüntü nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| scaleX | **float** | Bu Küçük Resim'in x eksenindeki ölçeklendirme değeri. |
| scaleY | **float** | Bu Küçük Resim'in y eksenindeki ölçeklendirme değeri. |

### Dönüş Değeri

Görüntü nesnesi [IImage](../../iimage/)

## ISlide::GetImage() metod

Gerçek boyutunun %20'si kadar bir Küçük Resim Görüntü nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```

### Dönüş Değeri

Görüntü nesnesi [IImage](../../iimage/)

## ISlide::GetImage(System::Drawing::Size) metod

Belirtilen boyutta bir görüntü nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Görüntü nesnesi [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metod

Belirtilen parametrelerle bir Küçük Resim tiff bitmap nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Tiff seçenekleri. |

### Dönüş Değeri

Görüntü nesnesi [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metod

Bir Küçük Resim Bitmap nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | İşleme seçenekleri. |

### Dönüş Değeri

Görüntü nesnesi [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metod

Özel ölçeklendirme ile bir Küçük Resim Bitmap nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | İşleme seçenekleri. |
| scaleX | **float** | Bu Küçük Resim'in x eksenindeki ölçeklendirme değeri. |
| scaleY | **float** | Bu Küçük Resim'in y eksenindeki ölçeklendirme değeri. |

### Dönüş Değeri

Görüntü nesnesi [IImage](../../iimage/)

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metod

Belirtilen boyutta bir Küçük Resim Bitmap nesnesi döndürür.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Parametreler

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | İşleme seçenekleri. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Oluşturulacak görüntünün boyutu. |

### Dönüş Değeri

Görüntü nesnesi [IImage](../../iimage/)

## İlgili

* Tip Tanımı [SharedPtr](../../../system/sharedptr/)
* Sınıf [IImage](../../iimage/)
* Sınıf [ISlide](../)
* Sınıf [Size](../../../system.drawing/size/)
* Sınıf [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Sınıf [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Ad Alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)