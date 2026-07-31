---
title: IndexOf()
second_title: Aspose.Slides untuk Referensi API C++
description: Mengembalikan indeks aturan yang ditentukan dalam koleksi.
type: docs
weight: 118
url: /id/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) method


Mengembalikan indeks aturan yang ditentukan dalam koleksi.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nama font yang akan dicari. |

### Nilai Kembalian

Indeks font atau -1 jika font tidak ditemukan dalam daftar.

## Catatan



```cpp
// Buat sebuah aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Dapatkan indeks Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IFontFallBackRule](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)