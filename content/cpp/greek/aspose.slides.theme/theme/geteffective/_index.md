---
title: GetEffective()
second_title: Αναφορά API Aspose.Slides για C++
description: Ανακτά τα αποτελεσματικά δεδομένα του θέματος με την εφαρμοσμένη κληρονομικότητα.
type: docs
weight: 53
url: /el/aspose.slides.theme/theme/geteffective/
---
## Theme::GetEffective() μέθοδος


Ανακτά τα αποτελεσματικά δεδομένα θέματος με την εφαρμοσμένη κληρονομικότητα.

```cpp
System::SharedPtr<IThemeEffectiveData> Aspose::Slides::Theme::Theme::GetEffective() override
```


### Τιμή Επιστροφής

Ένα [IThemeEffectiveData](../../ithemeeffectivedata/).
## Παρατηρήσεις



Αυτό το παράδειγμα δείχνει την λήψη των αποτελεσματικών ιδιοτήτων του θέματος. 
```cpp
auto pres = MakeObject<Presentation>(u"MyPresentation.pptx");
auto effectiveTheme = pres->get_Slides()->idx_get(0)->get_ThemeManager()->get_OverrideTheme()->GetEffective();

Console::WriteLine(String(u"Font scheme name: ") + effectiveTheme->get_FontScheme()->get_Name());
Console::WriteLine(String(u"Major latin font: ") + effectiveTheme->get_FontScheme()->get_Major()->get_LatinFont()->get_FontName());
Console::WriteLine(String(u"Minor latin font: ") + effectiveTheme->get_FontScheme()->get_Minor()->get_LatinFont()->get_FontName());
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IThemeEffectiveData](../../ithemeeffectivedata/)
* Κλάση [Theme](../)
* Χώρος ονομάτων [Aspose::Slides::Theme](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)