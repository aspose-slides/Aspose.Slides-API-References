---
title: ToArray()
second_title: Aspose.Slides untuk Referensi API C++
description: Membuat dan mengembalikan array dengan semua font FallBack untuk aturan ini.
type: docs
weight: 105
url: /id/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() metode


Membuat dan mengembalikan array dengan semua font FallBack untuk aturan ini.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### Nilai Kembali

Array dari [System::String](../../../system/string/)
## Catatan



```cpp
// Buat sebuah aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Dapatkan semua nama font sebagai array
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) metode


Membuat dan mengembalikan array dengan semua font FallBack dari rentang yang ditentukan dalam daftar.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startIndex | **int32_t** | Indeks font pertama yang akan ditambahkan. |
| count | **int32_t** | Jumlah font yang akan ditambahkan. |

### Nilai Kembali

Array dari [System::String](../../../system/string/)
## Catatan



```cpp
// Buat sebuah aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Dapatkan dua nama font terakhir sebagai array
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [IFontFallBackRule](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)