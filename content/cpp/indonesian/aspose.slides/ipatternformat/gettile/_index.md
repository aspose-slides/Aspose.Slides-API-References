---
title: GetTile()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat gambar ubin untuk isian pola dengan warna yang ditentukan.
type: docs
weight: 53
url: /id/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method

Membuat gambar ubin untuk isian pola dengan warna yang ditentukan.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | Latar belakang [System::Drawing::Color](../../../system.drawing/color/) untuk pola. |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | Latar depan [System::Drawing::Color](../../../system.drawing/color/) untuk pola. |

### Nilai Kembali

Ubin [IImage](../../iimage/).

## IPatternFormat::GetTile(System::Drawing::Color) method

Membuat gambar ubin untuk isian pola.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | [System::Drawing::Color](../../../system.drawing/color/) default, yang didefinisikan dalam objek StyleEx milik ShapeEx. Warna isian dapat bergantung pada ini. |

### Nilai Kembali

Ubin [IImage](../../iimage/).

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IImage](../../iimage/)
* Kelas [Color](../../../system.drawing/color/)
* Kelas [IPatternFormat](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)