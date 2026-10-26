---
title: idx_get()
second_title: Aspose.Slides για C++ API Reference
description: Λαμβάνει τον κανόνα στον καθορισμένο δείκτη. Μόνο για ανάγνωση IFontFallBackRule.
type: docs
weight: 1
url: /el/aspose.slides/ifontfallbackrulescollection/idx_get/
---
## IFontFallBackRulesCollection::idx_get(int32_t) μέθοδος


Λαμβάνει τον κανόνα στον καθορισμένο δείκτη. Μόνο για ανάγνωση [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
virtual System::SharedPtr<IFontFallBackRule> Aspose::Slides::IFontFallBackRulesCollection::idx_get(int32_t index)=0
```

## Παρατηρήσεις



```cpp
auto pres = MakeObject<Presentation>();
//Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Προσθήκη πολλών κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Ανάκτηση αντικειμένου του πρώτου κανόνα στη συλλογή
auto firstRule = rulesList->idx_get(0);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontFallBackRule](../../ifontfallbackrule/)
* Κλάση [IFontFallBackRulesCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)