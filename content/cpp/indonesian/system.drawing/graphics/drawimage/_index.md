---
title: DrawImage()
second_title: Referensi API Aspose.Slides untuk C++
description: TIDAK DIIMPLEMENTASIKAN.
type: docs
weight: 430
url: /id/system.drawing/graphics/drawimage/
---
## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<Point\>\&) metode

TIDAK DIIMPLEMENTASIKAN.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<Point> &destPoints)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | DIABAIKAN |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | DIABAIKAN |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::ArrayPtr\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::ArrayPtr<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destPoints | const [System::ArrayPtr](../../../system/arrayptr/)\<[PointF](../../pointf/)\>\& | Array yang berisi tiga titik yang mendefinisikan sebuah paralelogram pada permukaan gambar untuk menempatkan gambar |
| srcRect | const [RectangleF](../../rectanglef/)\& | Persegi panjang yang mendefinisikan wilayah gambar yang ditentukan untuk digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran yang digunakan oleh parameter **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Menentukan informasi warna dan gamma untuk gambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::ArrayView\<PointF\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::ArrayView<PointF> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destPoints | const System::Details::ArrayView\<[PointF](../../pointf/)\>\& | Tampilan array yang berisi tiga titik yang mendefinisikan sebuah paralelogram pada permukaan gambar untuk menempatkan gambar |
| srcRect | const [RectangleF](../../rectanglef/)\& | Persegi panjang yang mendefinisikan wilayah gambar yang ditentukan untuk digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran yang digunakan oleh parameter **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Menentukan informasi warna dan gamma untuk gambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const System::Details::StackArray\<PointF, N\>\&, const RectangleF\&, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
template<std::size_t> void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const System::Details::StackArray<PointF, N> &destPoints, const RectangleF &srcRect, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destPoints | const System::Details::StackArray\<[PointF](../../pointf/), N\>\& | Array stack yang berisi tiga titik yang mendefinisikan sebuah paralelogram pada permukaan gambar untuk menempatkan gambar |
| srcRect | const [RectangleF](../../rectanglef/)\& | Persegi panjang yang mendefinisikan wilayah gambar yang ditentukan untuk digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran yang digunakan oleh parameter **srcRect** |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Menentukan informasi warna dan gamma untuk gambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int) metode

Menggambar gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| x | int | Koordinat X dari sudut kiri atas gambar yang digambar |
| y | int | Koordinat Y dari sudut kiri atas gambar yang digambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float) metode

Menggambar gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| x | **float** | Koordinat X dari sudut kiri atas gambar yang digambar |
| y | **float** | Koordinat Y dari sudut kiri atas gambar yang digambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Point) metode

Menggambar gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Point pt)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| pt | [Point](../../point/) | Lokasi sudut kiri atas gambar yang digambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, PointF) metode

Menggambar gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, PointF pt)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| pt | [PointF](../../pointf/) | Lokasi sudut kiri atas gambar yang digambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, int, int) metode

Menggambar gambar yang ditentukan ke persegi panjang yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, int width, int height)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| x | int | Koordinat X dari sudut kiri atas persegi panjang tempat gambar digambar |
| y | int | Koordinat Y dari sudut kiri atas persegi panjang tempat gambar digambar |
| width | int | Lebar persegi panjang tempat gambar digambar |
| height | int | Tinggi persegi panjang tempat gambar digambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, float, float) metode

Menggambar gambar yang ditentukan ke persegi panjang yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, float width, float height)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| x | **float** | Koordinat X dari sudut kiri atas persegi panjang tempat gambar digambar |
| y | **float** | Koordinat Y dari sudut kiri atas persegi panjang tempat gambar digambar |
| width | **float** | Lebar persegi panjang tempat gambar digambar |
| height | **float** | Tinggi persegi panjang tempat gambar digambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, RectangleF, RectangleF, GraphicsUnit) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, RectangleF destRect, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destRect | [RectangleF](../../rectanglef/) | Persegi panjang tempat gambar digambar |
| srcRect | [RectangleF](../../rectanglef/) | Persegi panjang yang mendefinisikan wilayah gambar yang ditentukan untuk digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran yang digunakan oleh parameter **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, Rectangle, GraphicsUnit) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destRect | [Rectangle](../../rectangle/) | Persegi panjang tempat gambar digambar |
| srcRect | [Rectangle](../../rectangle/) | Persegi panjang yang mendefinisikan wilayah gambar yang ditentukan untuk digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran yang digunakan oleh parameter **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, int, int, Rectangle, GraphicsUnit) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, int x, int y, Rectangle srcRect, GraphicsUnit srcUnit)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| x | int | Koordinat X dari sudut kiri atas persegi panjang tempat gambar digambar |
| y | int | Koordinat Y dari sudut kiri atas persegi panjang tempat gambar digambar |
| srcRect | [Rectangle](../../rectangle/) | Persegi panjang yang mendefinisikan wilayah gambar yang ditentukan untuk digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran yang digunakan oleh parameter **srcRect** |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const Rectangle\&) metode

Menggambar gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const Rectangle &rect)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| rect | const [Rectangle](../../rectangle/)\& | Persegi panjang tempat gambar digambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const RectangleF\&) metode

Menggambar gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const RectangleF &rect)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| rect | const [RectangleF](../../rectanglef/)\& | Persegi panjang tempat gambar digambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan ke persegi panjang yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destRect | [Rectangle](../../rectangle/) | Persegi panjang tempat gambar digambar |
| srcX | int | Koordinat X dari sudut kiri atas persegi panjang yang menentukan bagian gambar yang digambar |
| srcY | int | Koordinat Y dari sudut kiri atas persegi panjang yang menentukan bagian gambar yang digambar |
| srcWidth | int | Lebar persegi panjang yang menentukan bagian gambar yang digambar |
| srcHeight | int | Tinggi persegi panjang yang menentukan bagian gambar yang digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran di mana parameter **srcX**, **srcY**, **srcWidth** dan **srcHeight** ditentukan |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Menentukan informasi warna dan gamma untuk gambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan ke persegi panjang yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destRect | [Rectangle](../../rectangle/) | Persegi panjang tempat gambar digambar |
| srcX | **float** | Koordinat X dari sudut kiri atas persegi panjang yang menentukan bagian gambar yang digambar |
| srcY | **float** | Koordinat Y dari sudut kiri atas persegi panjang yang menentukan bagian gambar yang digambar |
| srcWidth | **float** | Lebar persegi panjang yang menentukan bagian gambar yang digambar |
| srcHeight | **float** | Tinggi persegi panjang yang menentukan bagian gambar yang digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran di mana parameter **srcX**, **srcY**, **srcWidth** dan **srcHeight** ditentukan |
| imgAttributes | const [Imaging::ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)\& | Menentukan informasi warna dan gamma untuk gambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan ke persegi panjang yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destRect | [Rectangle](../../rectangle/) | Persegi panjang tempat gambar digambar |
| srcX | int | Koordinat X dari sudut kiri atas persegi panjang yang menentukan bagian gambar yang digambar |
| srcY | int | Koordinat Y dari sudut kiri atas persegi panjang yang menentukan bagian gambar yang digambar |
| srcWidth | int | Lebar persegi panjang yang menentukan bagian gambar yang digambar |
| srcHeight | int | Tinggi persegi panjang yang menentukan bagian gambar yang digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran di mana parameter **srcX**, **srcY**, **srcWidth** dan **srcHeight** ditentukan |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan ke persegi panjang yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destRect | [Rectangle](../../rectangle/) | Persegi panjang tempat gambar digambar |
| srcX | **float** | Koordinat X dari sudut kiri atas persegi panjang yang menentukan bagian gambar yang digambar |
| srcY | **float** | Koordinat Y dari sudut kiri atas persegi panjang yang menentukan bagian gambar yang digambar |
| srcWidth | **float** | Lebar persegi panjang yang menentukan bagian gambar yang digambar |
| srcHeight | **float** | Tinggi persegi panjang yang menentukan bagian gambar yang digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran di mana parameter **srcX**, **srcY**, **srcWidth**, dan **srcHeight** ditentukan |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metode

TIDAK DIIMPLEMENTASIKAN.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort) metode

TIDAK DIIMPLEMENTASIKAN.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, int, int, int, int, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metode

TIDAK DIIMPLEMENTASIKAN.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, int srcX, int srcY, int srcWidth, int srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, Rectangle, float, float, float, float, GraphicsUnit, const Imaging::ImageAttributesPtr\&, Graphics::DrawImageAbort, IntPtr) metode

TIDAK DIIMPLEMENTASIKAN.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, Rectangle destRect, float srcX, float srcY, float srcWidth, float srcHeight, GraphicsUnit srcUnit, const Imaging::ImageAttributesPtr &imgAttributes, Graphics::DrawImageAbort callback, IntPtr callbackData)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&, RectangleF, GraphicsUnit) metode

TIDAK DIIMPLEMENTASIKAN.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints, RectangleF srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<PointF\>\&) metode

TIDAK DIIMPLEMENTASIKAN.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<PointF> &destPoints)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit) metode

TIDAK DIIMPLEMENTASIKAN.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit)
```

## Graphics::DrawImage(const SharedPtr\<Image\>\&, const ArrayPtr\<Point\>\&, Rectangle, GraphicsUnit, const SharedPtr\<Imaging::ImageAttributes\>\&) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, const ArrayPtr<Point> &destPoints, Rectangle srcRect, GraphicsUnit srcUnit, const SharedPtr<Imaging::ImageAttributes> &imageAttr)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| destPoints | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../point/)\>\& | Array yang berisi tiga titik yang mendefinisikan sebuah paralelogram pada permukaan gambar untuk menempatkan gambar |
| srcRect | [Rectangle](../../rectangle/) | Persegi panjang yang mendefinisikan wilayah gambar yang ditentukan untuk digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran yang digunakan oleh parameter **srcRect** |
| imageAttr | const [SharedPtr](../../../system/sharedptr/)\<[Imaging::ImageAttributes](../../../system.drawing.imaging/imageattributes/)\>\& | Menentukan informasi warna dan gamma untuk gambar |

## Graphics::DrawImage(const SharedPtr\<Image\>\&, float, float, RectangleF, GraphicsUnit) metode

Menggambar wilayah yang ditentukan dari gambar yang ditentukan pada lokasi yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawImage(const SharedPtr<Image> &image, float x, float y, RectangleF srcRect, GraphicsUnit srcUnit)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang akan digambar |
| x | **float** | Koordinat X dari sudut kiri atas persegi panjang tempat gambar digambar |
| y | **float** | Koordinat Y dari sudut kiri atas persegi panjang tempat gambar digambar |
| srcRect | [RectangleF](../../rectanglef/) | Persegi panjang yang mendefinisikan wilayah gambar yang ditentukan untuk digambar |
| srcUnit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran yang digunakan oleh parameter **srcRect** |

## Lihat Juga

* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [ImageAttributesPtr](../../../system.drawing.imaging/imageattributesptr/)
* Typedef [DrawImageAbort](../drawimageabort/)
* Class [Image](../../image/)
* Class [Point](../../point/)
* Class [Graphics](../)
* Class [PointF](../../pointf/)
* Class [RectangleF](../../rectanglef/)
* Class [Rectangle](../../rectangle/)
* Class [ImageAttributes](../../../system.drawing.imaging/imageattributes/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)