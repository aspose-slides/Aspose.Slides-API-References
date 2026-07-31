---
title: TextureBrush()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru dari kelas TextureBrush yang menggunakan gambar yang ditentukan.
type: docs
weight: 1
url: /id/system.drawing/texturebrush/texturebrush/
---
## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode) konstruktor

Membuat sebuah instance baru dari kelas [TextureBrush](../) yang menggunakan gambar yang ditentukan.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode=Drawing2D::WrapMode::Tile)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specifies how the brush object is tiled |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, RectangleF, const SharedPtr\<Imaging::ImageAttributes\>\&) konstruktor

Membuat sebuah instance baru dari kelas [TextureBrush](../) yang menggunakan gambar yang ditentukan.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, RectangleF dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| dst_rect | [RectangleF](../../rectanglef/) | Specifies the bounding rectangle for the brush |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | The image attributes |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Rectangle, const SharedPtr\<Imaging::ImageAttributes\>\&) konstruktor

Membuat sebuah instance baru dari kelas [TextureBrush](../) yang menggunakan gambar yang ditentukan.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Rectangle dst_rect, const SharedPtr<Imaging::ImageAttributes> &image_attrs=nullptr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| dst_rect | [Rectangle](../../rectangle/) | Specifies the bounding rectangle for the brush |
| image_attrs | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | The image attributes |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, RectangleF) konstruktor

Membuat sebuah instance baru dari kelas [TextureBrush](../) yang menggunakan gambar yang ditentukan.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, RectangleF dst_rect)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specifies how the brush object is tiled |
| dst_rect | [RectangleF](../../rectanglef/) | Specifies the bounding rectangle for the brush |

## TextureBrush::TextureBrush(const SharedPtr\<Image\>\&, Drawing2D::WrapMode, Rectangle) konstruktor

Membuat sebuah instance baru dari kelas [TextureBrush](../) yang menggunakan gambar yang ditentukan.

```cpp
System::Drawing::TextureBrush::TextureBrush(const SharedPtr<Image> &image, Drawing2D::WrapMode wrap_mode, Rectangle dst_rect)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | An image used by the brush to fill the interior of a shape |
| wrap_mode | [Drawing2D::WrapMode](../../../system.drawing.drawing2d/wrapmode/) | Specifies how the brush object is tiled |
| dst_rect | [Rectangle](../../rectangle/) | Specifies the bounding rectangle for the brush |

## Lihat Juga

* Enum [WrapMode](../../../system.drawing.drawing2d/wrapmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Image](../../image/)
* Kelas [TextureBrush](../)
* Kelas [RectangleF](../../rectanglef/)
* Kelas [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Kelas [Rectangle](../../rectangle/)
* Ruang Nama [System::Drawing](../../)
* Library [Aspose.Slides](../../../)