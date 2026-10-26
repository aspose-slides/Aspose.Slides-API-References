---
title: SetSize()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengatur ukuran slide berdasarkan tipe dan menskala konten yang ada.
type: docs
weight: 53
url: /id/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metode

Mengatur ukuran slide berdasarkan tipe dan menskala konten yang ada.

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Ukuran slide bawaan yang akan diterapkan. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Mode penskalaan konten yang akan digunakan. |

## Catatan

Menetapkan nilai apa pun selain [SlideSizeType::Custom](../../slidesizetype/) menyesuaikan [SlideSize::get_Size](../get_size/) berdasarkan tipe yang dipilih, sambil mempertahankan [SlideSize::get_Orientation](../get_orientation/). 

## SlideSize::SetSize(float, float, SlideSizeScaleType) metode

Mengatur dimensi slide secara eksplisit dan menskala konten yang ada.

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | **float** | Lebar slide baru, dalam poin. |
| height | **float** | Tinggi slide baru, dalam poin. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Mode penskalaan konten yang akan digunakan. |

## Catatan

Ini mengatur ulang properti [SlideSize::get_Type](../get_type/) ke [SlideSizeType::Custom](../../slidesizetype/) dan menetapkan [Orientation](../../orientation/). 

## Lihat Juga

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Kelas [SlideSize](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)