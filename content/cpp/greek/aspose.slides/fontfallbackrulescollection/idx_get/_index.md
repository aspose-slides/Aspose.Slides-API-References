---
title: idx_get()
second_title: Αναφορά API του Aspose.Slides για C++
description: Λαμβάνει τον κανόνα στη συγκεκριμένη θέση. Μόνο για ανάγνωση IFontFallBackRule.
type: docs
weight: 66
url: /el/aspose.slides/fontfallbackrulescollection/idx_get/
---
## FontFallBackRulesCollection::idx_get(int32_t) μέθοδος

Λαμβάνει τον κανόνα στη συγκεκριμένη θέση. Μόνο για ανάγνωση [IFontFallBackRule](../../ifontfallbackrule/).

```cpp
System::SharedPtr<IFontFallBackRule> Aspose::Slides::FontFallBackRulesCollection::idx_get(int32_t index) override
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
* Κλάση [FontFallBackRulesCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)