---
title: GetImages()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan objek Image untuk semua slide dalam presentasi.
type: docs
weight: 456
url: /id/aspose.slides/presentation/getimages/
---
## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>) metode


Mengembalikan objek Image untuk semua slide dalam presentasi.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | opsi Tiff. |

### Nilai Kembalian

Objek Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>) metode


Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | opsi Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, dimulai dari 1. |

### Nilai Kembalian

Objek Thumbnail Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metode


Mengembalikan objek Thumbnail Image untuk semua slide dalam presentasi dengan skala khusus.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | opsi Tiff. |
| scaleX | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

### Nilai Kembalian

Objek Thumbnail Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, float, float) metode


Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi dengan skala khusus.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, float scaleX, float scaleY) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | opsi Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, dimulai dari 1. |
| scaleX | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

### Nilai Kembalian

Objek Thumbnail Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metode


Mengembalikan objek Thumbnail Image untuk semua slide dalam presentasi dengan ukuran tertentu.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | opsi Tiff. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran gambar yang akan dibuat. |

### Nilai Kembalian

Objek Thumbnail Image.

## Presentation::GetImages(System::SharedPtr\<Export::IRenderingOptions\>, System::ArrayPtr\<int32_t\>, System::Drawing::Size) metode


Mengembalikan objek Thumbnail Image untuk slide tertentu dalam presentasi dengan ukuran tertentu.

```cpp
System::ArrayPtr<System::SharedPtr<IImage>> Aspose::Slides::Presentation::GetImages(System::SharedPtr<Export::IRenderingOptions> options, System::ArrayPtr<int32_t> slides, System::Drawing::Size imageSize) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | opsi Tiff. |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Array dengan posisi slide, dimulai dari 1. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran gambar yang akan dibuat. |

### Nilai Kembalian

Objek Thumbnail Image.

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IImage](../../iimage/)
* Kelas [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Kelas [Presentation](../)
* Kelas [Size](../../../system.drawing/size/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)