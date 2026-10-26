---
title: GetScriptFontMap()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan kamus semua definisi font skrip dalam presentasi.
type: docs
weight: 79
url: /id/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() Metode


Mengembalikan kamus semua definisi font skrip dalam presentasi.

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### Nilai Kembali

Kamus yang memetakan kode skrip ke nama font.
## Keterangan




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IDictionary](../../../system.collections.generic/idictionary/)
* Kelas [String](../../../system/string/)
* Kelas [Fonts](../)
* Ruang Nama [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)