---
title: DrawString()
second_title: Referensi API Aspose.Slides untuk C++
description: Menggambar string yang ditentukan pada lokasi yang ditentukan menggunakan font dan kuas yang ditentukan.
type: docs
weight: 365
url: /id/system.drawing/graphics/drawstring/
---
## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, PointF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metode


Menggambar string yang ditentukan pada lokasi yang ditentukan menggunakan font dan kuas yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, PointF topLeft, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | String yang akan digambar |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Font yang akan digunakan |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objek [Brush](../../brush/) untuk menggambar |
| topLeft | [PointF](../../pointf/) | Menentukan lokasi sudut kiri atas string yang digambar |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Menentukan format string |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, RectangleF, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metode


Menggambar string yang ditentukan dalam persegi panjang yang ditentukan menggunakan font dan kuas yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, RectangleF layoutRectangle, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | String yang akan digambar |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Font yang akan digunakan |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objek [Brush](../../brush/) untuk menggambar |
| layoutRectangle | [RectangleF](../../rectanglef/) | Menentukan persegi panjang tempat menggambar string |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Menentukan format string |

## Graphics::DrawString(const String\&, const SharedPtr\<Font\>\&, const SharedPtr\<Brush\>\&, float, float, const System::SharedPtr\<System::Drawing::StringFormat\>\&) metode


Menggambar string yang ditentukan pada lokasi yang ditentukan menggunakan font dan kuas yang ditentukan.

```cpp
void System::Drawing::Graphics::DrawString(const String &str, const SharedPtr<Font> &font, const SharedPtr<Brush> &brush, float x, float y, const System::SharedPtr<System::Drawing::StringFormat> &stringFormat=nullptr)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | const [String](../../../system/string/)\& | String yang akan digambar |
| font | const [SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\>\& | Font yang akan digunakan |
| brush | const [SharedPtr](../../../system/sharedptr/)\<[Brush](../../brush/)\>\& | Objek [Brush](../../brush/) untuk menggambar |
| x | **float** | Koordinat X lokasi sudut kiri atas string yang digambar |
| y | **float** | Koordinat Y lokasi sudut kiri atas string yang digambar |
| stringFormat | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Drawing::StringFormat](../../stringformat/)\>\& | Menentukan format string |

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [Font](../../font/)
* Kelas [Brush](../../brush/)
* Kelas [PointF](../../pointf/)
* Kelas [StringFormat](../../stringformat/)
* Kelas [Graphics](../)
* Kelas [RectangleF](../../rectanglef/)
* Ruang Nama [System::Drawing](../../)
* Library [Aspose.Slides](../../../)