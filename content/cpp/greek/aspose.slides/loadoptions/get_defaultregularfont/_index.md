---
title: get_DefaultRegularFont()
second_title: Aspose.Slides για C++ API Αναφορά
description: "Επιστρέφει τη γραμματοσειρά Regular που χρησιμοποιείται στην περίπτωση που η πηγή γραμματοσειράς δεν βρεθεί. Διαβάστε System::String."
type: docs
weight: 27
url: /el/aspose.slides/loadoptions/get_defaultregularfont/
---
## LoadOptions::get_DefaultRegularFont() μέθοδος

Επιστρέφει τη γραμματοσειρά Κανονική που χρησιμοποιείται στην περίπτωση που η πηγή γραμματοσειράς δεν βρεθεί. Διαβάστε [System::String](../../../system/string/).

```cpp
System::String Aspose::Slides::LoadOptions::get_DefaultRegularFont() override
```

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε προεπιλεγμένες γραμματοσειρές για την απόδοση του PowerPoint [Presentation](../../presentation/). 
```cpp
// Χρησιμοποιήστε επιλογές φόρτωσης για να ορίσετε τις προεπιλεγμένες κανονικές και ασιατικές γραμματοσειρές
System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>(LoadFormat::Auto);
loadOptions->set_DefaultRegularFont(u"Wingdings");
loadOptions->set_DefaultAsianFont(u"Wingdings");

// Φορτώστε την παρουσίαση
auto pptx = System::MakeObject<Presentation>(u"DefaultFonts.pptx", loadOptions);
// Δημιουργήστε μικρογραφία διαφάνειας
auto slide = pptx->get_Slides()->idx_get(0);
slide->GetThumbnail(1.0f, 1.0f)->Save(u"output_out.png", System::Drawing::Imaging::ImageFormat::get_Png());

// Δημιουργήστε PDF
pptx->Save(u"output_out.pdf", SaveFormat::Pdf);
// Δημιουργήστε XPS
pptx->Save(u"output_out.xps", SaveFormat::Xps);
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [LoadOptions](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)