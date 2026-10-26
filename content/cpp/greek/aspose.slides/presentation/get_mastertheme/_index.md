---
title: get_MasterTheme()
second_title: Aspose.Slides για C++ Αναφορά API
description: "Επιστρέφει το κύριο θέμα. Μόνο για ανάγνωση Theme::IMasterTheme."
type: docs
weight: 404
url: /el/aspose.slides/presentation/get_mastertheme/
---
## Presentation::get_MasterTheme() μέθοδος

Επιστρέφει το κύριο θέμα. Μόνο για ανάγνωση [Theme::IMasterTheme](../../../aspose.slides.theme/imastertheme/).

```cpp
System::SharedPtr<Theme::IMasterTheme> Aspose::Slides::Presentation::get_MasterTheme() override
```

## Σημειώσεις

Τα ακόλουθα παραδείγματα δείχνουν πώς να αλλάξετε ένα εφέ θέματος τροποποιώντας τμήματα στοιχείων του PowerPoint [Presentation](../). 
```cpp
// Δημιουργήστε ένα αντικείμενο παρουσίασης που αντιπροσωπεύει ένα αρχείο παρουσίασης
auto pres = System::MakeObject<Presentation>(u"Subtle_Moderate_Intense.pptx");
auto masterTheme = pres->get_MasterTheme();
auto formatScheme = masterTheme->get_FormatScheme();

formatScheme->get_LineStyles()->idx_get(0)->get_FillFormat()->get_SolidFillColor()->set_Color(System::Drawing::Color::get_Red());
formatScheme->get_FillStyles()->idx_get(2)->set_FillType(FillType::Solid);
formatScheme->get_FillStyles()->idx_get(2)->get_SolidFillColor()->set_Color(System::Drawing::Color::get_ForestGreen());
formatScheme->get_EffectStyles()->idx_get(2)->get_EffectFormat()->get_OuterShadowEffect()->set_Distance(10.0f);
pres->Save(u"Design_04_Subtle_Moderate_Intense-out.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IMasterTheme](../../../aspose.slides.theme/imastertheme/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)