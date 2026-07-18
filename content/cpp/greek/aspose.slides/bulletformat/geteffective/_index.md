---
title: GetEffective()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης κουκίδας με την εφαρμογή της κληρονομίας.
type: docs
weight: 248
url: /el/aspose.slides/bulletformat/geteffective/
---
## BulletFormat::GetEffective() method


Λαμβάνει τα αποτελεσματικά δεδομένα μορφοποίησης κουκίδας με την εφαρμογή της κληρονομίας.

```cpp
System::SharedPtr<IBulletFormatEffectiveData> Aspose::Slides::BulletFormat::GetEffective() override
```


### Τιμή Επιστροφής

Ένα [IBulletFormatEffectiveData](../../ibulletformateffectivedata/).
## Παρατηρήσεις



Αυτό το παράδειγμα δείχνει την απόκτηση ορισμένων αποτελεσματικών ιδιοτήτων μορφοποίησης κουκίδας. 
```cpp
using namespace System;
using namespace Aspose::Slides;

auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto shape = AsCast<Aspose::Slides::IAutoShape>(pres->get_Slides()->idx_get(0)->get_Shapes()->idx_get(0));
auto effectiveBulletFormat = shape->get_TextFrame()->get_Paragraphs()->idx_get(0)->get_ParagraphFormat()->get_Bullet()->GetEffective();

Console::WriteLine(String(u"Bullet type: ") + ObjectExt::ToString(effectiveBulletFormat->get_Type()));
if (effectiveBulletFormat->get_Type() == Aspose::Slides::BulletType::Numbered)
{
    Console::WriteLine(String(u"Numbered style: ") + ObjectExt::ToString(effectiveBulletFormat->get_NumberedBulletStyle()));
    Console::WriteLine(String(u"Starting number: ") + effectiveBulletFormat->get_NumberedBulletStartWith());
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBulletFormatEffectiveData](../../ibulletformateffectivedata/)
* Class [BulletFormat](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)