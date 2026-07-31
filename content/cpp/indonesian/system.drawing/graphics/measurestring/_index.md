---
title: MeasureString()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan ukuran string yang ditentukan ketika digambar dengan font yang ditentukan dalam format yang ditentukan.
type: docs
weight: 521
url: /id/system.drawing/graphics/measurestring/
---
## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, PointF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Mengembalikan ukuran string yang ditentukan ketika digambar dengan font yang ditentukan dalam format yang ditentukan.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, PointF const &origin=PointF(0, 0), System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | String yang ukurannya akan dihitung |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Font yang digunakan untuk menggambar string |
| origin | [PointF](../../pointf/) const\& | Menentukan lokasi sudut kiri atas string |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Menentukan format string |

### Nilai Kembalian

Sebuah objek [SizeF](../../sizef/) yang mewakili ukuran string dalam satuan pengukuran yang ditentukan oleh properti PageUnit dari objek Grapphics saat ini.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, int, System::SharedPtr\<StringFormat\> const\&) const method

Mengembalikan ukuran string yang ditentukan ketika digambar dengan font yang ditentukan dalam format yang ditentukan.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, int width, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | String yang ukurannya akan dihitung |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Font yang digunakan untuk menggambar string |
| width | int | Lebar maksimum string |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Menentukan format string |

### Nilai Kembalian

Sebuah objek [SizeF](../../sizef/) yang mewakili ukuran string dalam satuan pengukuran yang ditentukan oleh properti PageUnit dari objek Grapphics saat ini.

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&, int\&, int\&) const method

BELUM DIIMPLEMENTASIKAN.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat, int &charactersFitted, int &linesFilled) const
```

## Graphics::MeasureString(String const\&, System::SharedPtr\<Font\> const\&, SizeF const\&, System::SharedPtr\<StringFormat\> const\&) const method

Mengembalikan ukuran string yang ditentukan ketika digambar dengan font yang ditentukan dalam format yang ditentukan.

```cpp
SizeF System::Drawing::Graphics::MeasureString(String const &str, System::SharedPtr<Font> const &font, SizeF const &layoutArea, System::SharedPtr<StringFormat> const &stringFormat=nullptr) const
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| str | [String](../../../system/string/) const\& | String yang ukurannya akan dihitung |
| font | [System::SharedPtr](../../../system/sharedptr/)\<[Font](../../font/)\> const\& | Font yang digunakan untuk menggambar string |
| layoutArea | [SizeF](../../sizef/) const\& | Area tata letak maksimum string |
| stringFormat | [System::SharedPtr](../../../system/sharedptr/)\<[StringFormat](../../stringformat/)\> const\& | Menentukan format string |

### Nilai Kembalian

Sebuah objek [SizeF](../../sizef/) yang mewakili ukuran string dalam satuan pengukuran yang ditentukan oleh properti PageUnit dari objek Grapphics saat ini.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [SizeF](../../sizef/)
* Kelas [String](../../../system/string/)
* Kelas [Font](../../font/)
* Kelas [PointF](../../pointf/)
* Kelas [StringFormat](../../stringformat/)
* Kelas [Graphics](../)
* Ruang Nama [System::Drawing](../../)
* Pustaka [Aspose.Slides](../../../)