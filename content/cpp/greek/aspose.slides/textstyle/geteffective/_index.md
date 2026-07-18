---
title: GetEffective()
second_title: Aspose.Slides για το C++ Αναφορά API
description: Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης στυλ κειμένου με την κληρονομικότητα εφαρμοσμένη.
type: docs
weight: 27
url: /el/aspose.slides/textstyle/geteffective/
---
## TextStyle::GetEffective() μέθοδος

Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης στυλ κειμένου με την κληρονομικότητα εφαρμοσμένη.

```cpp
System::SharedPtr<ITextStyleEffectiveData> Aspose::Slides::TextStyle::GetEffective() override
```


### Τιμή Επιστροφής

Ένα [ITextStyleEffectiveData](../../itextstyleeffectivedata/).
## Παρατηρήσεις


Αυτό το παράδειγμα δείχνει την λήψη ορισμένων αποτελεσματικών ιδιοτήτων στυλ κειμένου.
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveTextStyle = shape->get_TextFrame()->get_TextFrameFormat()->get_TextStyle()->GetEffective();

for (int32_t i = 0; i <= 8; i++)
{
    auto effectiveStyleLevel = effectiveTextStyle->GetLevel(i);
    Console::WriteLine(String(u"= Effective paragraph formatting for style level #") + i + u" =");

    Console::WriteLine(String(u"Depth: ") + effectiveStyleLevel->get_Depth());
    Console::WriteLine(String(u"Indent: ") + effectiveStyleLevel->get_Indent());
    Console::WriteLine(String(u"Alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_Alignment()));
    Console::WriteLine(String(u"Font alignment: ") + ObjectExt::ToString(effectiveStyleLevel->get_FontAlignment()));
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ITextStyleEffectiveData](../../itextstyleeffectivedata/)
* Κλάση [TextStyle](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)