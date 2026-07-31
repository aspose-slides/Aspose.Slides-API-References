---
title: ToArray()
second_title: Referensi API Aspose.Slides untuk C++
description: Membuat dan mengembalikan sebuah array dengan semua font FallBack untuk aturan ini.
type: docs
weight: 144
url: /id/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() metode

Membuat dan mengembalikan sebuah array dengan semua font FallBack untuk aturan ini.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### Nilai Kembali

Array dari [System::String](../../../system/string/)
## Catatan

```cpp
// Buat aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Dapatkan semua nama font sebagai array.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) metode

Membuat dan mengembalikan sebuah array dengan semua font FallBack dari rentang yang ditentukan dalam daftar.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
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
// Buat aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Dapatkan dua nama font terakhir sebagai array.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [FontFallBackRule](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)