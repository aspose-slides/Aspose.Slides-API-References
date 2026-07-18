---
title: get_DisableFontLigatures()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων γραφής. Όταν οριστεί σε true, οι συνδέσεις γραφής θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε false.
type: docs
weight: 40
url: /el/aspose.slides.export/irenderingoptions/get_disablefontligatures/
---
## IRenderingOptions::get_DisableFontLigatures() μέθοδος


Λαμβάνει μια τιμή που υποδεικνύει εάν το κείμενο αποδίδεται χωρίς τη χρήση συνδέσεων γραφής. Όταν οριστεί σε **true**, οι συνδέσεις γραφής θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε **false**.

```cpp
virtual bool Aspose::Slides::Export::IRenderingOptions::get_DisableFontLigatures()=0
```

## Παρατηρήσεις


Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση των συνδέσεων γραφής στην απόδοση κειμένου

System::ArrayPtr<System::SharedPtr<IImage>> renderedSlides = pres->GetImages(options);
for (int32_t index = 0; index < renderedSlides->get_Length(); index++)
{
    auto slideImage = renderedSlides[index];
    slideImage->Save(System::String::Format(u"slide-{0}.png", index));
}
```

## Δείτε επίσης

* Κλάση [IRenderingOptions](../)
* Χώρος ονομάτων [Aspose::Slides::Export](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)