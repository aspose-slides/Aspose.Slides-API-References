---
title: RemoveAt()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus font FallBack pada indeks yang ditentukan dalam daftar.
type: docs
weight: 131
url: /id/aspose.slides/fontfallbackrule/removeat/
---
## FontFallBackRule::RemoveAt(int32_t) metode

Menghapus font FallBack pada indeks yang ditentukan dalam daftar.

```cpp
void Aspose::Slides::FontFallBackRule::RemoveAt(int32_t index) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol dari font yang akan dihapus. |
## Keterangan

```cpp
// Buat aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Menghapus Tahoma dari daftar.
newRule->RemoveAt(2);
```

## Lihat Juga

* Kelas [FontFallBackRule](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)