---
title: set_DocumentLevelFontSources()
second_title: Referensi API Aspose.Slides untuk C++
description: Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. Font ini tersedia untuk presentasi sepanjang masa hidupnya dan tidak dibagikan dengan presentasi lain
type: docs
weight: 222
url: /id/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) metode

Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. Font ini tersedia untuk presentasi sepanjang masa hidupnya dan tidak dibagikan dengan presentasi lain

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## Catatan

Contoh berikut menunjukkan cara menentukan font khusus yang digunakan dengan PowerPoint [Presentation](../../presentation/).
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// bekerja dengan presentasi
// CustomFont1, CustomFont2 serta font dari folder assets\fonts & global\fonts serta subfoldernya tersedia untuk presentasi
```

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFontSources](../../ifontsources/)
* Kelas [LoadOptions](../)
* Ruang Nama [Aspose::Slides](../../)
* Perpustakaan [Aspose.Slides](../../../)