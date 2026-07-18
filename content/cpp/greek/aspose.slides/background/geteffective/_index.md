---
title: GetEffective()
second_title: Aspose.Slides για C++ API Αναφορά
description: Λαμβάνει τα αποτελεσματικά δεδομένα φόντου με την κληρονομικότητα να έχει εφαρμοστεί.
type: docs
weight: 118
url: /el/aspose.slides/background/geteffective/
---
## Background::GetEffective() μέθοδος


Λαμβάνει τα αποτελεσματικά δεδομένα φόντου με την κληρονομικότητα να έχει εφαρμοστεί.

```cpp
System::SharedPtr<IBackgroundEffectiveData> Aspose::Slides::Background::GetEffective() override
```


### Τιμή Επιστροφής

Ένα [IBackgroundEffectiveData](../../ibackgroundeffectivedata/).
## Παρατηρήσεις



Αυτό το παράδειγμα παρουσιάζει τη λήψη των αποτελεσματικών ιδιοτήτων φόντου. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveBackground = pres->get_Slides()->idx_get(0)->get_Background()->GetEffective();
Console::WriteLine(String(u"Background fill type: ") + ObjectExt::ToString(effectiveBackground->get_FillFormat()->get_FillType()));
Console::WriteLine(String(u"Any effects applied: ") + !effectiveBackground->get_EffectFormat()->get_IsNoEffects());
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IBackgroundEffectiveData](../../ibackgroundeffectivedata/)
* Κλάση [Background](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)