---
title: get_InkEffect()
second_title: Αναφορά API του Aspose.Slides για C++
description: "Αποκτά τον τύπο εφέ μελάνης (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ της γραμμής μελάνης. Η τιμή αναλύεται από την ιδιότητα του πινέλου \"inkEffects\". Εάν δεν καθοριστεί κάποιο αναγνωρισμένο εφέ, InkEffectType::NotDefined επιστρέφεται."
type: docs
weight: 53
url: /el/aspose.slides.ink/iinkbrush/get_inkeffect/
---
## IInkBrush::get_InkEffect() μέθοδος

Αποκτά τον τύπο του εφέ μελάνης (π.χ., Galaxy, Gold, Silver) που ορίζει το οπτικό στυλ του χτυπήματος μελάνης. Η τιμή αναλύεται από την ιδιότητα του πινέλου \"inkEffects\". Εάν δεν έχει καθοριστεί αναγνωρισμένο εφέ, [InkEffectType::NotDefined](../../inkeffecttype/) επιστρέφεται.

```cpp
virtual InkEffectType Aspose::Slides::Ink::IInkBrush::get_InkEffect()=0
```

## Παρατηρήσεις

Παράδειγμα:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"Presentation.pptx");
System::SharedPtr<Ink> ink = System::AsCast<Ink>(pres->get_Slide(0)->get_Shape(0));
System::SharedPtr<IInkBrush> brush = ink->get_Traces()->idx_get(0)->get_Brush();
System::Console::WriteLine(u"InkEffects = {0}", brush->get_InkEffect());
```

## Δείτε επίσης

* Απαρίθμηση [InkEffectType](../../inkeffecttype/)
* Κλάση [IInkBrush](../)
* Χώρος ονομάτων [Aspose::Slides::Ink](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)