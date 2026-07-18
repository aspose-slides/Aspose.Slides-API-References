---
title: GetEffective()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης πλαισίου κειμένου με την εφαρμοσμένη κληρονομικότητα.
type: docs
weight: 391
url: /el/aspose.slides/textframeformat/geteffective/
---
## TextFrameFormat::GetEffective() μέθοδος

Επιστρέφει τα αποτελεσματικά δεδομένα μορφοποίησης του πλαισίου κειμένου με την εφαρμοσμένη κληρονομικότητα.

```cpp
System::SharedPtr<ITextFrameFormatEffectiveData> Aspose::Slides::TextFrameFormat::GetEffective() override
```

### Τιμή Επιστροφής

A [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/).

## Παρατηρήσεις

Αυτό το παράδειγμα δείχνει την ανάκτηση ορισμένων από τις αποτελεσματικές ιδιότητες μορφοποίησης του πλαισίου κειμένου. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextFrameFormat = shape->get_TextFrame()->get_TextFrameFormat()->GetEffective();

Console::WriteLine(String(u"Anchoring type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AnchoringType()));
Console::WriteLine(String(u"Autofit type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_AutofitType()));
Console::WriteLine(String(u"Text vertical type: ") + ObjectExt::ToString(effectiveTextFrameFormat->get_TextVerticalType()));
Console::WriteLine(u"Margins");
Console::WriteLine(String(u"   Left: ") + effectiveTextFrameFormat->get_MarginLeft());
Console::WriteLine(String(u"   Top: ") + effectiveTextFrameFormat->get_MarginTop());
Console::WriteLine(String(u"   Right: ") + effectiveTextFrameFormat->get_MarginRight());
Console::WriteLine(String(u"   Bottom: ") + effectiveTextFrameFormat->get_MarginBottom());
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ITextFrameFormatEffectiveData](../../itextframeformateffectivedata/)
* Κλάση [TextFrameFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)