---
title: SetScriptFont()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan nama font ke tag skrip tertentu, yang menentukan bagaimana teks skrip tersebut akan dirender dalam presentasi.
type: docs
weight: 105
url: /id/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) metode

Menetapkan nama font ke tag skrip tertentu, yang menentukan bagaimana teks skrip tersebut akan dirender dalam presentasi.

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kode skrip BCP-47 (mis., "Arab", "Hebr", "Hans") yang mengidentifikasi sistem penulisan. |
| fontName | [System::String](../../../system/string/) | Nama font yang akan ditetapkan ke skrip yang ditentukan. |

## Catatan

Contoh ini menunjukkan cara mengatur font untuk skrip Arab menjadi "Segoe UI": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Lihat Juga

* Kelas [String](../../../system/string/)
* Kelas [Fonts](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)