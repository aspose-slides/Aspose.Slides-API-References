---
title: BeginContainer()
second_title: Referensi API Aspose.Slides untuk C++
description: Menyimpan sebuah kontainer dengan keadaan saat ini dari objek ini, membuka dan menggunakan kontainer baru, dan mengembalikan kontainer yang disimpan.
type: docs
weight: 976
url: /id/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() metode

Menyimpan kontainer dengan keadaan saat ini dari objek ini, membuka dan menggunakan kontainer baru, dan mengembalikan kontainer yang disimpan.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) metode

Menyimpan kontainer dengan keadaan saat ini dari objek ini, membuka dan menggunakan kontainer baru, dan mengembalikan kontainer yang disimpan.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | Persegi panjang yang menentukan transformasi skala dari kontainer baru. Digunakan bersama dengan **srcrect** |
| srcrect | [Rectangle](../../rectangle/) | Persegi panjang yang menentukan transformasi skala dari kontainer baru. Digunakan bersama dengan **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Nilai yang menentukan satuan ukuran dari kontainer baru |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) metode

Menyimpan kontainer dengan keadaan saat ini dari objek ini, membuka dan menggunakan kontainer baru, dan mengembalikan kontainer yang disimpan.

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | Persegi panjang yang menentukan transformasi skala dari kontainer baru. Digunakan bersama dengan **srcrect** |
| srcrect | [RectangleF](../../rectanglef/) | Persegi panjang yang menentukan transformasi skala dari kontainer baru. Digunakan bersama dengan **dstrect** |
| unit | [GraphicsUnit](../../graphicsunit/) | Nilai yang menentukan satuan ukuran dari kontainer baru |

## Lihat Juga

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Class [RectangleF](../../rectanglef/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)