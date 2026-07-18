---
title: get_FontsManager()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει τον διαχειριστή γραμματοσειρών. Μόνο για ανάγνωση IFontsManager.
type: docs
weight: 157
url: /el/aspose.slides/presentation/get_fontsmanager/
---
## Presentation::get_FontsManager() μέθοδος

Επιστρέφει τον διαχειριστή γραμματοσειρών. Μόνο για ανάγνωση [IFontsManager](../../ifontsmanager/).

```cpp
System::SharedPtr<IFontsManager> Aspose::Slides::Presentation::get_FontsManager() override
```

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να προσθέσετε ενσωματωμένες γραμματοσειρές στο PowerPoint [Presentation](../).
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

// Αποθήκευση της παρουσίασης
presentation->Save(u"AddEmbeddedFont_out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontsManager](../../ifontsmanager/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)