---
title: Font()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat sebuah instance baru dari kelas Font yang mewakili font yang ada yang ditentukan dengan gaya font yang ditentukan.
type: docs
weight: 1
url: /id/system.drawing/font/font/
---
## Font::Font(const SharedPtr\<Font\>\&, FontStyle) konstruktor


Membuat sebuah instance baru dari kelas [Font](../) yang mewakili font yang ada yang ditentukan dengan gaya font yang ditentukan.

```cpp
System::Drawing::Font::Font(const SharedPtr<Font> &prototype, FontStyle new_style)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| prototype | const [SharedPtr](../../../system/sharedptr/)\<[Font](../)\>\& | Font yang ada untuk membuat yang baru darinya |
| new_style | [FontStyle](../../fontstyle/) | Gaya font yang diterapkan pada font baru |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, FontStyle, GraphicsUnit, uint8_t, bool) konstruktor


Membuat sebuah instance baru dari kelas [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Keluarga font dari font baru |
| em_size | **float** | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter **unit** |
| style | [FontStyle](../../fontstyle/) | Gaya font baru |
| unit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran font baru |
| gdi_charset | **uint8_t** | Set karakter GDI yang akan digunakan untuk font baru |
| gdi_vertical_font | **bool** | Benar jika font baru diturunkan dari font vertikal GDI |

## Font::Font(const SharedPtr\<FontFamily\>\&, float, GraphicsUnit) konstruktor


Membuat sebuah instance baru dari kelas [Font](../).

```cpp
System::Drawing::Font::Font(const SharedPtr<FontFamily> &family, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family | const [SharedPtr](../../../system/sharedptr/)\<[FontFamily](../../fontfamily/)\>\& | Keluarga font dari font baru |
| em_size | **float** | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran font baru |

## Font::Font(const String\&, float, FontStyle, GraphicsUnit, uint8_t, bool) konstruktor


Membuat sebuah instance baru dari kelas [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, FontStyle style, GraphicsUnit unit=GraphicsUnit::Point, uint8_t gdi_charset=1, bool gdi_vertical_font=false)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Nama keluarga font dari font baru |
| em_size | **float** | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter **unit** |
| style | [FontStyle](../../fontstyle/) | Gaya font baru |
| unit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran font baru |
| gdi_charset | **uint8_t** | Set karakter GDI yang akan digunakan untuk font baru |
| gdi_vertical_font | **bool** | Benar jika font baru diturunkan dari font vertikal GDI |

## Font::Font(const String\&, float, GraphicsUnit) konstruktor


Membuat sebuah instance baru dari kelas [Font](../).

```cpp
System::Drawing::Font::Font(const String &family_name, float em_size, GraphicsUnit unit=GraphicsUnit::Point)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| family_name | const [String](../../../system/string/)\& | Nama keluarga font dari font baru |
| em_size | **float** | Ukuran em dari font baru dalam satuan yang ditentukan oleh parameter **unit** |
| unit | [GraphicsUnit](../../graphicsunit/) | Satuan pengukuran font baru |

## Lihat Juga

* Enum [FontStyle](../../fontstyle/)
* Enum [GraphicsUnit](../../graphicsunit/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Font](../)
* Class [FontFamily](../../fontfamily/)
* Class [String](../../../system/string/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)