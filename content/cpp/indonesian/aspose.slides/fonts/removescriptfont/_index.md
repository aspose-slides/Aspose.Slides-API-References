---
title: RemoveScriptFont()
second_title: Referensi API Aspose.Slides untuk C++
description: Menghapus pengaturan font yang terkait dengan tag skrip tertentu dari koleksi font tema.
type: docs
weight: 118
url: /id/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) metode

Menghapus pengaturan font yang terkait dengan tag skrip tertentu dari koleksi font tema.

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kode skrip BCP-47 yang pengaturan fontnya harus dihapus. |

## Keterangan

Contoh ini menunjukkan cara menghapus pemetaan font untuk skrip Ibrani:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [Fonts](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)