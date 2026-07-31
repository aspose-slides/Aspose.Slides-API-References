---
title: Clone()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat salinan dari objek saat ini.
type: docs
weight: 183
url: /id/system.drawing/bitmap/clone/
---
## Bitmap::Clone() metode


Membuat salinan dari objek saat ini.

```cpp
virtual SharedPtr<Image> System::Drawing::Bitmap::Clone() override
```


### Nilai Kembalian

Salinan dari objek saat ini.

## Bitmap::Clone(Rectangle, Imaging::PixelFormat) metode


Membuat objek [Bitmap](../) yang mewakili salinan dari wilayah gambar bitmap yang diwakili oleh objek saat ini.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(Rectangle rect, Imaging::PixelFormat format)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Rektangel yang menentukan wilayah yang akan disalin |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format piksel untuk [Bitmap](../) baru |

### Nilai Kembalian

Objek [Bitmap](../) yang dibuat

## Bitmap::Clone(RectangleF, Imaging::PixelFormat) metode


Membuat objek [Bitmap](../) yang mewakili salinan dari wilayah gambar bitmap yang diwakili oleh objek saat ini.

```cpp
SharedPtr<Bitmap> System::Drawing::Bitmap::Clone(RectangleF rect, Imaging::PixelFormat format)
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Rektangel yang menentukan wilayah yang akan disalin |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format piksel untuk [Bitmap](../) baru |

### Nilai Kembalian

Objek [Bitmap](../) yang dibuat

## Lihat Juga

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../../image/)
* Class [Bitmap](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)