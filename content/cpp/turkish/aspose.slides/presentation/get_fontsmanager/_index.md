---
title: get_FontsManager()
second_title: Aspose.Slides for C++ API Referansı
description: Yazı tipi yöneticisini döndürür. Salt okunur IFontsManager.
type: docs
weight: 157
url: /tr/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() metodu


Yazı tipleri yöneticisini döndürür. Salt okunur [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Açıklamalar


Aşağıdaki örnek, gömülü yazı tiplerini PowerPoint [Presentation](../)'a eklemeyi gösterir. 
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




## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [IFontsManager](../../ifontsmanager/)
* Sınıf [Presentation](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)