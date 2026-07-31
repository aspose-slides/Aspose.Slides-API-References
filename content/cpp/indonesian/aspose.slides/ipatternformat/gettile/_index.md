---
title: GetTile()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan.
type: docs
weight: 53
url: /id/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) metode

Membuat gambar ubin untuk pengisian pola dengan warna yang ditentukan.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Latar belakang [System::Drawing::Color](../../../system.drawing/color/) untuk pola. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Latar depan [System::Drawing::Color](../../../system.drawing/color/) untuk pola. |

### Nilai Kembalian

Ubin [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## IPatternFormat::GetTile(System::Drawing::Color) metode

Membuat gambar ubin untuk pengisian pola.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Argumen

| Parameter | Type | Deskripsi |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | Warna default [System::Drawing::Color](../../../system.drawing/color/), yang didefinisikan dalam objek StyleEx milik ShapeEx. Warna pengisian dapat bergantung pada ini. |

### Nilai Kembalian

Ubin [System::Drawing::Bitmap](../../../system.drawing/bitmap/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IImage](../../iimage/)
* Kelas [Color](../../../system.drawing/color/)
* Kelas [IPatternFormat](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)