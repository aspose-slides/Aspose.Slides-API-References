---
title: get_FontsManager()
second_title: Referensi API Aspose.Slides untuk C++
description: Mengembalikan manajer font. Hanya-baca IFontsManager.
type: docs
weight: 157
url: /id/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() metode


Mengembalikan manajer font. Hanya-baca [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Catatan


Contoh berikut menunjukkan cara menambahkan font tersemat ke PowerPoint [Presentation](../). 
```cpp
auto presentation = System::MakeObject<Presentation>(u"Fonts.pptx");
System::ArrayPtr<System::SharedPtr<IFontData>> allFonts = presentation->get_FontsManager()->GetFonts();
System::ArrayPtr<System::SharedPtr<IFontData>> embeddedFonts = presentation->get_FontsManager()->GetEmbeddedFonts();

for (auto&& font : allFonts)
{
    if (!embeddedFonts->Contains(font))
    {
        presentation->get_FontsManager()->AddEmbeddedFont(font, EmbedFontCharacters::All);
    }
}

// Save the presentation
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```




## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Kelas [IFontsManager](../../ifontsmanager/)
* Kelas [Presentation](../)
* Ruang nama [Aspose::Slides](../../)
* Pustaka [Aspose.Slides](../../../)