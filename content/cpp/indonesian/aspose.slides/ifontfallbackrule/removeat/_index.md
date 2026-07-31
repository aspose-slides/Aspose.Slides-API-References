---
title: RemoveAt()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus font FallBack pada indeks yang ditentukan dalam daftar.
type: docs
weight: 92
url: /id/aspose.slides/ifontfallbackrule/removeat/
---
## IFontFallBackRule::RemoveAt(int32_t) metode

Menghapus font FallBack pada indeks yang ditentukan dalam daftar.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::RemoveAt(int32_t index)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | **int32_t** | Indeks berbasis nol dari font yang akan dihapus. |
## Catatan

```cpp
// Buat aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Menghapus Tahoma dari daftar
newRule->RemoveAt(2);
```

## Lihat Juga

* Kelas [IFontFallBackRule](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)