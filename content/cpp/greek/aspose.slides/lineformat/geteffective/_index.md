---
title: GetEffective()
second_title: Aspose.Slides για C++ Αναφορά API
description: Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης γραμμής με εφαρμοσμένη την κληρονομικότητα.
type: docs
weight: 417
url: /el/aspose.slides/lineformat/geteffective/
---
## LineFormat::GetEffective() μέθοδος


Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης γραμμής με εφαρμοσμένη την κληρονομικότητα.

```cpp
System::SharedPtr<ILineFormatEffectiveData> Aspose::Slides::LineFormat::GetEffective() override
```


### Τιμή Επιστροφής

A [ILineFormatEffectiveData](../../ilineformateffectivedata/).
## Παρατηρήσεις



Αυτό το παράδειγμα δείχνει πώς να λαμβάνετε τις αποτελεσματικές ιδιότητες μορφοποίησης γραμμής του σχήματος. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveLineFormat = pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0)->get_LineFormat()->GetEffective();

Console::WriteLine(String(u"Style: ") + ObjectExt::ToString(effectiveLineFormat->get_Style()));
Console::WriteLine(String(u"Width: ") + effectiveLineFormat->get_Width());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectiveLineFormat->get_FillFormat()->get_FillType()));
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ILineFormatEffectiveData](../../ilineformateffectivedata/)
* Κλάση [LineFormat](../)
* Χώρος Ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)