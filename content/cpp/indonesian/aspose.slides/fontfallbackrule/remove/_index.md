---
title: Remove()
second_title: Aspose.Slides untuk Referensi API C++
description: Menghapus kemunculan pertama dari font FallBack tertentu dari daftar.
type: docs
weight: 118
url: /id/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) metode


Menghapus kemunculan pertama dari font FallBack tertentu dari daftar.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Arguments

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nama font yang akan dihapus dari daftar. |
## Keterangan



```cpp
// Buat aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Hapus Tahoma dari daftar.
newRule->Remove(u"Tahoma");
```


## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [FontFallBackRule](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)