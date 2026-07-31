---
title: GetImage()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan objek image dengan skala khusus.
type: docs
weight: 105
url: /id/aspose.slides/islide/getimage/
---
## ISlide::GetImage(float, float) metode


Mengembalikan objek Image dengan skala khusus.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(float scaleX, float scaleY)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| scaleX | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

### Nilai Kembali

Objek Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage() metode


Mengembalikan objek Thumbnail Image (20% dari ukuran sebenarnya).

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage()=0
```


### Nilai Kembali

Objek Image [System::Drawing::Bitmap](../../../system.drawing/bitmap/)

## ISlide::GetImage(System::Drawing::Size) metode


Mengembalikan objek Image dengan ukuran yang ditentukan.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::Drawing::Size imageSize)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran gambar yang akan dibuat. |

### Nilai Kembali

Objek Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::ITiffOptions\>) metode


Mengembalikan objek bitmap tiff Thumbnail dengan parameter yang ditentukan.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::ITiffOptions> options)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ITiffOptions](../../../aspose.slides.export/itiffoptions/)\> | Opsi Tiff. |

### Nilai Kembali

Objek Image.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>) metode


Mengembalikan objek Bitmap Thumbnail.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |

### Nilai Kembali

Objek Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, float, float) metode


Mengembalikan objek Bitmap Thumbnail dengan skala khusus.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, float scaleX, float scaleY)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
| scaleX | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu x. |
| scaleY | **float** | Nilai yang digunakan untuk menskalakan Thumbnail ini pada arah sumbu y. |

### Nilai Kembali

Objek Bitmap.

## ISlide::GetImage(System::SharedPtr\<Export::IRenderingOptions\>, System::Drawing::Size) metode


Mengembalikan objek Bitmap Thumbnail dengan ukuran yang ditentukan.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::ISlide::GetImage(System::SharedPtr<Export::IRenderingOptions> options, System::Drawing::Size imageSize)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Opsi rendering. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Ukuran gambar yang akan dibuat. |

### Nilai Kembali

Objek Bitmap.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IImage](../../iimage/)
* Kelas [ISlide](../)
* Kelas [Size](../../../system.drawing/size/)
* Kelas [ITiffOptions](../../../aspose.slides.export/itiffoptions/)
* Kelas [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)