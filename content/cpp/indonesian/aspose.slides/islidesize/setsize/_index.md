---
title: SetSize()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengatur ukuran slide berdasarkan tipe dan menskalakan konten yang ada. Menetapkan nilai apa pun selain SlideSizeType::Custom menyesuaikan ISlideSize::get_Size berdasarkan tipe yang dipilih, sambil mempertahankan ISlideSize::get_Orientation."
type: docs
weight: 53
url: /id/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) metode

Mengatur ukuran slide berdasarkan tipe dan menskalakan konten yang ada. Menetapkan nilai apa pun selain [SlideSizeType::Custom](../../slidesizetype/) menyesuaikan [ISlideSize::get_Size](../get_size/) berdasarkan tipe yang dipilih, sambil mempertahankan [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | Ukuran slide yang telah ditentukan untuk diterapkan. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Mode penskalaan konten yang akan digunakan. |

## Catatan

Menetapkan nilai apa pun selain [SlideSizeType::Custom](../../slidesizetype/) menyesuaikan [System::Drawing::Size](../../../system.drawing/size/) berdasarkan tipe yang dipilih, sambil mempertahankan [Orientation](../../orientation/). 

## ISlideSize::SetSize(float, float, SlideSizeScaleType) metode

Mengatur dimensi slide secara eksplisit dan menskalakan konten yang ada. Ini mengatur ulang nilai [ISlideSize::get_Type](../get_type/) menjadi [SlideSizeType::Custom](../../slidesizetype/) dan menetapkan [ISlideSize::get_Orientation](../get_orientation/).

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | **float** | Lebar slide baru, dalam poin. |
| height | **float** | Tinggi slide baru, dalam poin. |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | Mode penskalaan konten yang akan digunakan. |

## Catatan

Ini mengatur ulang properti [ISlideSize::get_Type](../get_type/) menjadi [SlideSizeType::Custom](../../slidesizetype/) dan menetapkan [Orientation](../../orientation/). 

## Lihat Juga

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* Kelas [ISlideSize](../)
* Namespace [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)