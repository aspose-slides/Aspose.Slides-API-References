---
title: GetImage()
second_title: Referensi API Aspose.Slides untuk C++
description: "Mengembalikan thumbnail shape. Tipe batas thumbnail shape ShapeThumbnailBounds::Shape digunakan secara default."
type: docs
weight: 651
url: /id/aspose.slides/shape/getimage/
---
## Shape::GetImage() metode

Mengembalikan thumbnail shape. [ShapeThumbnailBounds::Shape](../../shapethumbnailbounds/) tipe batas thumbnail shape digunakan secara default.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage() override
```

### Nilai Kembalian

[Shape](../) thumbnail.

## Shape::GetImage(ShapeThumbnailBounds, float, float) metode

Mengembalikan thumbnail shape.

```cpp
System::SharedPtr<IImage> Aspose::Slides::Shape::GetImage(ShapeThumbnailBounds bounds, float scaleX, float scaleY) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| bounds | [ShapeThumbnailBounds](../../shapethumbnailbounds/) | [Shape](../) tipe batas thumbnail. |
| scaleX | **float** | Skala X |
| scaleY | **float** | Skala Y |

### Nilai Kembalian

[Shape](../) thumbnail atau null jika [ShapeThumbnailBounds::Appearance](../../shapethumbnailbounds/) digunakan dan sebuah shape tidak memiliki elemen yang terlihat.

## Lihat Juga

* Enum [ShapeThumbnailBounds](../../shapethumbnailbounds/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IImage](../../iimage/)
* Kelas [Shape](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)