---
title: Bitmap()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat objek Bitmap baru dari gambar yang ada yang ditentukan.
type: docs
weight: 1
url: /id/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) constructor

Membuat objek [Bitmap](../) baru dari gambar yang ada yang ditentukan.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang ada untuk membuat gambar bitmap |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) constructor

Membuat objek [Bitmap](../) baru dari aliran yang ditentukan.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Aliran yang berisi data gambar |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(const String\&) constructor

Membuat objek [Bitmap](../) baru dari file yang ditentukan.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nama file yang berisi data gambar |

## Bitmap::Bitmap(const String\&, bool) constructor

Membuat objek [Bitmap](../) baru dari file yang ditentukan.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | Nama file yang berisi data gambar |
| useIcm | **bool** | IGNORED |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) constructor

Membuat objek [Bitmap](../) baru yang merepresentasikan gambar bitmap dengan lebar, tinggi, format piksel, dan data piksel yang ditentukan.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| width | int | Lebar gambar |
| height | int | Tinggi gambar |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | Format piksel gambar |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) constructor

Membuat objek [Bitmap](../) baru dari gambar yang ada yang ditentukan, skala ke ukuran yang ditentukan.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang ada untuk membuat gambar bitmap |
| size | const [Size](../../size/)\& | Ukuran gambar baru |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) constructor

Membuat objek [Bitmap](../) baru dari gambar yang ada yang ditentukan dengan lebar dan tinggi diskalakan ke nilai yang ditentukan.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | Gambar yang ada untuk membuat gambar bitmap |
| width | int | Lebar gambar baru |
| height | int | Tinggi gambar baru |

## Lihat Juga

* Enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [Image](../../image/)
* Kelas [Bitmap](../)
* Kelas [Stream](../../../system.io/stream/)
* Kelas [String](../../../system/string/)
* Kelas [Size](../../size/)
* Ruangnama [System::Drawing](../../)
* Library [Aspose.Slides](../../../)