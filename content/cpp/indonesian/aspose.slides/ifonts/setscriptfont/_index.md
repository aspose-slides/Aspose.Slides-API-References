---
title: SetScriptFont()
second_title: Referensi API Aspose.Slides untuk C++
description: Menetapkan nama font ke tag skrip tertentu, yang menentukan bagaimana teks skrip tersebut akan ditampilkan dalam presentasi.
type: docs
weight: 105
url: /id/aspose.slides/ifonts/setscriptfont/
---
## IFonts::SetScriptFont(System::String, System::String) metode

Menetapkan nama font ke tag skrip tertentu, yang menentukan bagaimana teks skrip tersebut akan ditampilkan dalam presentasi.

```cpp
virtual void Aspose::Slides::IFonts::SetScriptFont(System::String script, System::String fontName)=0
```

### Argumen

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kode skrip BCP-47 (mis., \"Arab\", \"Hebr\", \"Hans\") yang mengidentifikasi sistem penulisan. |
| fontName | [System::String](../../../system/string/) | Nama font yang akan diberikan ke skrip yang ditentukan. |
## Catatan

Contoh ini menunjukkan cara mengatur font untuk skrip Arab menjadi \"Segoe UI\": 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## Lihat Juga

* Class [String](../../../system/string/)
* Class [IFonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)