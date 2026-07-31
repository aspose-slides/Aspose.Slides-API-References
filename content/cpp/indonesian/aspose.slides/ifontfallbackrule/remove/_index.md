---
title: Remove()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus kemunculan pertama sebuah font FallBack tertentu dari daftar.
type: docs
weight: 79
url: /id/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) metode


Menghapus kemunculan pertama sebuah font FallBack tertentu dari daftar.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Nama font yang akan dihapus dari daftar. |
## Catatan



```cpp
// Buat aturan yang berisi daftar font.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Menghapus Tahoma dari daftar
newRule->Remove(u"Tahoma");
```


## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IFontFallBackRule](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)