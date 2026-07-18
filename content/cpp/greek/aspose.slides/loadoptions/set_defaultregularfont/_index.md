---
title: set_DefaultRegularFont()
second_title: Aspose.Slides για Αναφορά API C++
description: "Ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά. Γράψτε System::String."
type: docs
weight: 40
url: /el/aspose.slides/loadoptions/set_defaultregularfont/
---
## LoadOptions::set_DefaultRegularFont(System::String) μέθοδος

Ορίζει τη γραμματοσειρά Regular που χρησιμοποιείται όταν δεν βρεθεί η πηγαία γραμματοσειρά. Γράψτε [System::String](../../../system/string/).

```cpp
void Aspose::Slides::LoadOptions::set_DefaultRegularFont(System::String value) override
```

## Παρατηρήσεις

Το παρακάτω παράδειγμα δείχνει πώς να ορίσετε τις προεπιλεγμένες γραμματοσειρές για την απόδοση του PowerPoint [Presentation](../../presentation/). 
```cpp
// Χρησιμοποιήστε τις επιλογές φόρτωσης για να ορίσετε τις προεπιλεγμένες γραμματοσειρές regular και asian
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
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)