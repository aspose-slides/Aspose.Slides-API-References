---
title: Remove()
second_title: Aspose.Slides για C++ – Αναφορά API
description: Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου κανόνα FallBack από τη συλλογή.
type: docs
weight: 27
url: /el/aspose.slides/ifontfallbackrulescollection/remove/
---
## IFontFallBackRulesCollection::Remove(System::SharedPtr\<IFontFallBackRule\>) μέθοδος

Αφαιρεί την πρώτη εμφάνιση ενός συγκεκριμένου κανόνα FallBack από τη συλλογή.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Remove(System::SharedPtr<IFontFallBackRule> targetRule)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| targetRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Ο κανόνας που θα αφαιρεθεί από τη συλλογή. |

## Παρατηρήσεις

```cpp
auto pres = MakeObject<Presentation>();
//Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Προσθήκη πολλών κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
rulesList->Add(MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho"));
//Ανάκτηση του αντικειμένου του πρώτου κανόνα στη συλλογή
auto firstRule = rulesList->idx_get(0);
//Αφαίρεση
rulesList->Remove(firstRule);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontFallBackRule](../../ifontfallbackrule/)
* Κλάση [IFontFallBackRulesCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)