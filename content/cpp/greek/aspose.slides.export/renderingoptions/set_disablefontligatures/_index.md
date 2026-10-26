---
title: set_DisableFontLigatures()
second_title: Aspose.Slides για C++ API Αναφορά
description: Ορίζει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσμων. Όταν οριστεί σε true, οι σύνδεσμοι θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε false.
type: docs
weight: 53
url: /el/aspose.slides.export/renderingoptions/set_disablefontligatures/
---
## RenderingOptions::set_DisableFontLigatures(bool) μέθοδος

Ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσμων. Όταν οριστεί σε **true**, οι σύνδεσμοι θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε **false**.

```cpp
void Aspose::Slides::Export::RenderingOptions::set_DisableFontLigatures(bool value) override
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση συνδέσμων στην απόδοση κειμένου

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Δείτε επίσης

* Κλάση [RenderingOptions](../)
* Ονομαχώρος [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)