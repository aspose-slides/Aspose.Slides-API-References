---
title: GetEffective()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Λαμβάνει τα δεδομένα μορφοποίησης τμήματος με την εφαρμοσμένη κληρονομικότητα.
type: docs
weight: 131
url: /el/aspose.slides/portionformat/geteffective/
---
## PortionFormat::GetEffective() μέθοδος


Λαμβάνει τα δεδομένα μορφοποίησης τμήματος με την εφαρμογή κληρονομικότητας.

```cpp
System::SharedPtr<IPortionFormatEffectiveData> Aspose::Slides::PortionFormat::GetEffective() override
```


### Τιμή επιστροφής

Ένα [IPortionFormatEffectiveData](../../iportionformateffectivedata/).
## Σχόλια



Αυτό το παράδειγμα δείχνει την απόκτηση ορισμένων αποτελεσματικών ιδιοτήτων μορφοποίησης τμήματος. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectivePortionFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_Portions()->idx_get(0)->get_PortionFormat()->GetEffective();

Console::WriteLine(String(u"Latin font: ") + effectivePortionFormat->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Font height: ") + effectivePortionFormat->get_FontHeight());
Console::WriteLine(String(u"Fill type: ") + ObjectExt::ToString(effectivePortionFormat->get_FillFormat()->get_FillType()));
```

## Δείτε επίσης

* Ορισμός τύπου [SharedPtr](../../../system/sharedptr/)
* Κλάση [IPortionFormatEffectiveData](../../iportionformateffectivedata/)
* Κλάση [PortionFormat](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)