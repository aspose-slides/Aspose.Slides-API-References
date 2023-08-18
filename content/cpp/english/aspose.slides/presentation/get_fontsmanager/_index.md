---
title: get_FontsManager()
second_title: Aspose.Slides for C++ API Reference
description: Returns fonts manager. Read-only IFontsManager.
type: docs
weight: 157
url: /aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() method


Returns fonts manager. Read-only [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Remarks


The following example shows how to add embedded fonts to PowerPoint [Presentation](../). 
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




## See Also

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontsManager](../../ifontsmanager/)
* Class [Presentation](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)