---
title: SetClip()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan wilayah kliping dari permukaan gambar yang direpresentasikan oleh objek Graphics saat ini menjadi hasil operasi yang ditentukan yang menggabungkan wilayah klip saat ini dan wilayah yang ditentukan.
type: docs
weight: 690
url: /id/system.drawing/graphics/setclip/
---
## Graphics::SetClip(const SharedPtr\<Region\>\&, Drawing2D::CombineMode) metode

Mengatur wilayah kliping dari permukaan gambar yang direpresentasikan oleh objek [Graphics](../) saat ini menjadi hasil operasi yang ditentukan yang menggabungkan wilayah klip saat ini dan wilayah yang ditentukan.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Region> &region, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| region | const [SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(Rectangle, Drawing2D::CombineMode) metode

Mengatur wilayah kliping dari permukaan gambar yang direpresentasikan oleh objek [Graphics](../) saat ini menjadi hasil operasi yang ditentukan yang menggabungkan wilayah klip saat ini dan wilayah yang ditentukan.

```cpp
void System::Drawing::Graphics::SetClip(Rectangle rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [Rectangle](../../rectangle/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(RectangleF, Drawing2D::CombineMode) metode

Mengatur wilayah kliping dari permukaan gambar yang direpresentasikan oleh objek [Graphics](../) saat ini menjadi hasil operasi yang ditentukan yang menggabungkan wilayah klip saat ini dan wilayah yang ditentukan.

```cpp
void System::Drawing::Graphics::SetClip(RectangleF rect, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| rect | [RectangleF](../../rectanglef/) | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Graphics::SetClip(const SharedPtr\<Graphics\>\&, Drawing2D::CombineMode) metode

TIDAK DIIMPLEMENTASIKAN.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Graphics> &graphics, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

## Graphics::SetClip(const SharedPtr\<Drawing2D::GraphicsPath\>\&, Drawing2D::CombineMode) metode

Mengatur wilayah kliping dari permukaan gambar yang direpresentasikan oleh objek [Graphics](../) saat ini menjadi hasil operasi yang ditentukan yang menggabungkan wilayah klip saat ini dan wilayah yang ditentukan oleh sebuah jalur grafik.

```cpp
void System::Drawing::Graphics::SetClip(const SharedPtr<Drawing2D::GraphicsPath> &path, Drawing2D::CombineMode combineMode=Drawing2D::CombineMode::Replace)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[Drawing2D::GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)\>\& | Specifies a region to combine |
| combineMode | [Drawing2D::CombineMode](../../../system.drawing.drawing2d/combinemode/) | Specifies the combining operation |

## Lihat Juga

* Enum [CombineMode](../../../system.drawing.drawing2d/combinemode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Region](../../region/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Class [GraphicsPath](../../../system.drawing.drawing2d/graphicspath/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)