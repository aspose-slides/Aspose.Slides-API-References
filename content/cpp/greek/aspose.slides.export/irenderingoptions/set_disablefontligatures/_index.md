---
title: set_DisableFontLigatures()
second_title: Aspose.Slides για την αναφορά API C++
description: Ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση λογών. Όταν οριστεί σε true, οι λογές θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε false.
type: docs
weight: 53
url: /el/aspose.slides.export/irenderingoptions/set_disablefontligatures/
---
## IRenderingOptions::set_DisableFontLigatures(bool) μέθοδος

Ορίζει μια τιμή που υποδεικνύει αν το κείμενο αποδίδεται χωρίς τη χρήση λογών. Όταν οριστεί σε **true**, οι λογές θα απενεργοποιηθούν στην παραγόμενη έξοδο. Από προεπιλογή, αυτή η ιδιότητα ορίζεται σε **false**.

```cpp
virtual void Aspose::Slides::Export::IRenderingOptions::set_DisableFontLigatures(bool value)=0
```

## Παρατηρήσεις

Παράδειγμα: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<RenderingOptions> options = System::MakeObject<RenderingOptions>();
options->set_DisableFontLigatures(true); // Απενεργοποίηση λογών στην απόδοση κειμένου

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