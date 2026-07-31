---
title: GetScriptFont()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan nama font yang terkait dengan tag skrip tertentu dari tema presentasi.
type: docs
weight: 92
url: /id/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) metode

Mendapatkan nama font yang terkait dengan tag skrip tertentu dari tema presentasi.

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kode skrip BCP-47 (mis., \"Latn\", \"Cyrl\", \"Jpan\") yang digunakan untuk mengidentifikasi sistem penulisan. |

### Nilai Kembalian

Nama font yang digunakan untuk skrip yang ditentukan, atau **null** jika skrip tidak didefinisikan.

## Catatan

Contoh ini menunjukkan cara mengambil font yang ditetapkan untuk skrip Cyrillic dalam tema presentasi.
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [IFonts](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)