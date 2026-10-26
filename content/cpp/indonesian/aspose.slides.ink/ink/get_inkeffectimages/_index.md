---
title: get_InkEffectImages()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan koleksi gambar khusus yang digunakan untuk mensimulasikan efek visual pada kuas tinta. Gambar ini digunakan saat merender tinta dengan nilai InkEffectType tertentu, seperti Galaxy, Rainbow, dll. Dengan menyediakan gambar Anda sendiri, Anda dapat mengontrol bagaimana setiap efek tinta muncul.
type: docs
weight: 14
url: /id/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() metode

Mendapatkan koleksi gambar khusus yang digunakan untuk mensimulasikan efek visual pada kuas tinta. Gambar ini digunakan saat merender tinta dengan nilai [InkEffectType](../../inkeffecttype/) tertentu, seperti Galaxy, Rainbow, dll. Dengan menyediakan gambar Anda sendiri, Anda dapat mengontrol bagaimana setiap efek tinta muncul.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Catatan

Properti ini memungkinkan mengganti tekstur efek tinta default dengan yang didefinisikan pengguna, yang terutama berguna ketika aset default dibatasi oleh lisensi atau tidak tersedia pada waktu berjalan.

Setiap entri dalam kamus harus mengaitkan nilai [InkEffectType](../../inkeffecttype/) dengan objek [IImage](../../../aspose.slides/iimage/) yang bersesuaian (misalnya, Bitmap, atau antarmuka gambar **Aspose**).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Lihat Juga

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IDictionary](../../../system.collections.generic/idictionary/)
* Class [IImage](../../../aspose.slides/iimage/)
* Class [Ink](../)
* Namespace [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)