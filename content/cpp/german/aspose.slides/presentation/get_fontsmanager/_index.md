---
title: get_FontsManager()
second_title: Aspose.Slides für C++ API Referenz
description: Gibt den Schriftarten-Manager zurück. Schreibgeschützt IFontsManager.
type: docs
weight: 157
url: /de/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() Methode

Gibt den Schriftarten-Manager zurück. Schreibgeschützt [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Hinweise

Das folgende Beispiel zeigt, wie man eingebettete Schriftarten zu PowerPoint [Presentation](../) hinzufügt. 
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


## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontsManager](../../ifontsmanager/)
* Klasse [Presentation](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)