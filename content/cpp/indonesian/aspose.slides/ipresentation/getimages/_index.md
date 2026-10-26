---
title: GetImages()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek Thumbnail Image untuk semua slide dalam presentasi.
type: docs
weight: 417
url: /id/aspose.slides/ipresentation/getimages/
---
## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) metode

Mengembalikan objek Thumbnail Image untuk semua slide dalam presentasi.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |

### Nilai Kembali

objek Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) metode

Mengembalikan objek Thumbnail Bitmap untuk slide yang ditentukan dalam presentasi.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, dimulai dari 1. |

### Nilai Kembali

objek Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metode

Mengembalikan objek Thumbnail Image untuk semua slide dalam presentasi dengan skala khusus.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
| scaleX | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu x. |
| scaleY | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu y. |

### Nilai Kembali

objek Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) metode

Mengembalikan objek Thumbnail Image untuk slide yang ditentukan dalam presentasi dengan skala khusus.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, dimulai dari 1. |
| scaleX | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu x. |
| scaleY | **float** | Nilai yang digunakan untuk memperbesar Thumbnail ini pada arah sumbu y. |

### Nilai Kembali

objek Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metode

Mengembalikan objek Thumbnail Image untuk semua slide dalam presentasi dengan ukuran yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran gambar yang akan dibuat. |

### Nilai Kembali

objek Bitmap.

## IPresentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) metode

Mengembalikan objek Thumbnail Image untuk slide yang ditentukan dalam presentasi dengan ukuran yang ditentukan.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::IPresentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, dimulai dari 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran gambar yang akan dibuat. |

### Nilai Kembali

objek Bitmap.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IImage](../../iimage/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Class [IPresentation](../)
* Class [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)