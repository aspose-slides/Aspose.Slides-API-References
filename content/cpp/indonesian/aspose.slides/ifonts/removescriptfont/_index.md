---
title: RemoveScriptFont()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus pengaturan font yang terkait dengan tag skrip tertentu dari koleksi font tema.
type: docs
weight: 118
url: /id/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) metode

Menghapus pengaturan font yang terkait dengan tag skrip tertentu dari koleksi font tema.

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kode skrip BCP-47 yang pengaturan fontnya harus dihapus. |
## Catatan

Contoh ini menunjukkan cara menghapus pemetaan font untuk skrip Ibrani: 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IFonts](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)