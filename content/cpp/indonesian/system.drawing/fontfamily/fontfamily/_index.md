---
title: FontFamily()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat instance baru dari kelas FontFamily yang mewakili keluarga font dengan nama yang ditentukan.
type: docs
weight: 1
url: /id/system.drawing/fontfamily/fontfamily/
---
## FontFamily::FontFamily(const String\&) konstruktor


Membuat instance baru dari kelas [FontFamily](../) yang mewakili keluarga font dengan nama yang ditentukan.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama keluarga font |

## FontFamily::FontFamily(const String\&, const SharedPtr\<Text::FontCollection\>\&) konstruktor


Membuat instance baru dari [FontFamily](../) dalam FontCollection yang ditentukan dengan nama yang ditentukan.

```cpp
System::Drawing::FontFamily::FontFamily(const String &name, const SharedPtr<Text::FontCollection> &font_collection)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | const [String](../../../system/string/)\& | Nama keluarga font |
| font_collection | const [SharedPtr](../../../system/sharedptr/)\<[Text::FontCollection](../../../system.drawing.text/fontcollection/)\>\& | FontCollection yang berisi instance ini. |

## FontFamily::FontFamily(Text::GenericFontFamilies) konstruktor


Membuat instance baru dari [FontFamily](../) dari keluarga font generik yang ditentukan.

```cpp
System::Drawing::FontFamily::FontFamily(Text::GenericFontFamilies generic_family)
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| generic_family | [Text::GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/) | Nilai GenericFontFamilies untuk membangun [FontFamily](../). |

## Lihat Juga

* Enum [GenericFontFamilies](../../../system.drawing.text/genericfontfamilies/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [String](../../../system/string/)
* Kelas [FontFamily](../)
* Kelas [FontCollection](../../../system.drawing.text/fontcollection/)
* ruang nama [System::Drawing](../../)
* Perpustakaan [Aspose.Slides](../../../)