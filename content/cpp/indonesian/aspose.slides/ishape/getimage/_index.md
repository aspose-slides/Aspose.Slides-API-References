---
title: GetImage()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengembalikan thumbnail shape. Tipe batas thumbnail shape ShapeThumbnailBounds::Shape digunakan secara default."
type: docs
weight: 547
url: /id/aspose.slides/ishape/getimage/
---
## IShape::GetImage() metode

Mengembalikan thumbnail shape. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) tipe batas thumbnail shape digunakan secara default.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage()=0
```

### Nilai Kembali

[Shape](../../shape/) thumbnail.

## IShape::GetImage(ShapeThumbnailBounds, float, float) metode

Mengembalikan thumbnail shape.

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IShape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../../shape/) tipe batas thumbnail. |
| scaleX | **float** | Skala X |
| scaleY | **float** | Skala Y |

### Nilai Kembali

[Shape](../../shape/) thumbnail atau null jika [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) digunakan dan sebuah shape tidak memiliki elemen yang terlihat.

## Lihat Juga

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IImage](../../iimage/)
* Kelas [IShape](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)