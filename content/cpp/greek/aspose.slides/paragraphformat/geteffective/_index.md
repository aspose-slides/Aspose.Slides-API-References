---
title: GetEffective()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης παραγράφου με την εφαρμογή της κληρονόμησης.
type: docs
weight: 365
url: /el/aspose.slides/paragraphformat/geteffective/
---
## ParagraphFormat::GetEffective() μέθοδος


Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης παραγράφου με την εφαρμογή της κληρονόμησης.

```cpp
System::SharedPtr<IParagraphFormatEffectiveData> Aspose::Slides::ParagraphFormat::GetEffective() override
```


### Τιμή Επιστροφής

Ένα [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/).
## Παρατηρήσεις



Αυτό το παράδειγμα δείχνει την λήψη ορισμένων αποτελεσματικών ιδιοτήτων μορφοποίησης παραγράφου. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveParagraphFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->GetEffective();

Console::WriteLine(String(u"Text alignment: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Alignment()));
Console::WriteLine(String(u"Indent: ") + effectiveParagraphFormat->get_Indent());
Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveParagraphFormat->get_Bullet()->get_Type()));
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IParagraphFormatEffectiveData](../../iparagraphformateffectivedata/)
* Κλάση [ParagraphFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)