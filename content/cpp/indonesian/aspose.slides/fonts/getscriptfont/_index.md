---
title: GetScriptFont()
second_title: Referensi API Aspose.Slides untuk C++
description: Mendapatkan nama font yang terkait dengan tag skrip tertentu dari tema presentasi.
type: docs
weight: 92
url: /id/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) metode


Mendapatkan nama font yang terkait dengan tag skrip tertentu dari tema presentasi.

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### Argumen

| Parameter | Type | Description |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | Kode skrip BCP-47 (misalnya "Latn", "Cyrl", "Jpan") yang digunakan untuk mengidentifikasi sistem penulisan. |

### Nilai Kembalian

Nama font yang digunakan untuk skrip yang ditentukan, atau **null** jika skrip tidak didefinisikan.

## Catatan



Contoh ini menunjukkan cara mengambil font yang ditetapkan untuk skrip Cyrillic dalam tema presentasi. 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## Lihat Juga

* Class [String](../../../system/string/)
* Class [Fonts](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)