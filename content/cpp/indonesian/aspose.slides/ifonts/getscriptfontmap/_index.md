---
title: GetScriptFontMap()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan kamus berisi semua definisi font skrip dalam presentasi.
type: docs
weight: 79
url: /id/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() metode


Mengembalikan sebuah kamus berisi semua definisi font skrip dalam presentasi.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```


### Nilai Kembalian

Sebuah kamus yang memetakan kode skrip ke nama font.
## Catatan




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
* Kelas [IFonts](../)
* Ruang Nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)