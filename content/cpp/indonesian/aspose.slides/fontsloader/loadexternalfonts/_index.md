---
title: LoadExternalFonts()
second_title: Referensi API Aspose.Slides untuk C++
description: Menambahkan folder tambahan untuk mencari font.
type: docs
weight: 1
url: /id/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String>) metode

Menambahkan folder tambahan untuk mencari font.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)<[System::String](../../../system/string/)> | Direktori untuk membaca font tambahan. |

## Keterangan

Contoh berikut menunjukkan cara memuat font khusus dari .TTF 
```cpp
// Jalur ke direktori dokumen.
System::String dataDir = u"C:\\";

// folder untuk mencari font
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Muat font dari direktori font khusus
FontsLoader::LoadExternalFonts(folders);

// Lakukan beberapa pekerjaan dan melakukan rendering presentasi/slide
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Bersihkan Cache Font
FontsLoader::ClearCache();
```

## Lihat Juga

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Kelas [String](../../../system/string/)
* Kelas [FontsLoader](../)
* Namespace [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)