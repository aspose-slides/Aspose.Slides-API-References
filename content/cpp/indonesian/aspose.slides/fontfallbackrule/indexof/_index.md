---
title: IndexOf()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan indeks dari aturan yang ditentukan dalam koleksi.
type: docs
weight: 157
url: /id/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) method


Mengembalikan indeks dari aturan yang ditentukan dalam koleksi.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nama font yang akan dicari. |

### Nilai Kembali

Indeks font atau -1 jika font tidak ditemukan dalam daftar.
## Catatan



```cpp
// Membuat aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Dapatkan indeks Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tah

oma");
```


## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [FontFallBackRule](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)