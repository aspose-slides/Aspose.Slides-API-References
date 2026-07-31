---
title: LockBits()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengunci sebuah Bitmap ke memori sistem.
type: docs
weight: 118
url: /id/system.drawing/bitmap/lockbits/
---
## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat) method

Mengunci [Bitmap](../) ke memori sistem.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Sebuah persegi panjang yang menentukan wilayah gambar yang akan dikunci |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Menentukan tingkat akses ke bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format data bitmap ini |

### Nilai Kembali

Pointer bersama ke objek BitmapData yang berisi informasi tentang operasi kunci yang dilakukan

## Bitmap::LockBits(const Rectangle\&, Imaging::ImageLockMode, Imaging::PixelFormat, const Imaging::BitmapDataPtr\&) method

Mengunci [Bitmap](../) ke memori sistem.

```cpp
Imaging::BitmapDataPtr System::Drawing::Bitmap::LockBits(const Rectangle &rect, Imaging::ImageLockMode flags, Imaging::PixelFormat format, const Imaging::BitmapDataPtr &bitmap_data)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | const [Rectangle](../../rectangle/)\& | Sebuah persegi panjang yang menentukan wilayah gambar yang akan dikunci |
| flags | [Imaging::ImageLockMode](../../../system.drawing.imaging/imagelockmode/) | Menentukan tingkat akses ke bitmap |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format data bitmap ini |
| bitmap_data | const [Imaging::BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)\& | Berisi informasi tentang operasi kunci |

### Nilai Kembali

Pointer bersama ke objek BitmapData yang berisi informasi tentang operasi kunci yang dilakukan

## Lihat Juga

* Enum [ImageLockMode](../../../system.drawing.imaging/imagelockmode/)
* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [BitmapDataPtr](../../../system.drawing.imaging/bitmapdataptr/)
* Class [Rectangle](../../rectangle/)
* Class [Bitmap](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)