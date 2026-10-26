---
title: Add()
second_title: Αναφορά API του Aspose.Slides για C++
description: Προσθέτει έναν νέο κανόνα FallBack στο τέλος της συλλογής.
type: docs
weight: 14
url: /el/aspose.slides/ifontfallbackrulescollection/add/
---
## IFontFallBackRulesCollection::Add(System::SharedPtr\<IFontFallBackRule\>) μέθοδος

Προσθέτει έναν νέο κανόνα FallBack στο τέλος της συλλογής.

```cpp
virtual void Aspose::Slides::IFontFallBackRulesCollection::Add(System::SharedPtr<IFontFallBackRule> sourceRule)=0
```

### Ορίσματα

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| sourceRule | [System::SharedPtr](../../../system/sharedptr/)\<[IFontFallBackRule](../../ifontfallbackrule/)\> | Καθορισμένος κανόνας για προσθήκη |

## Παρατηρήσεις

```cpp
auto pres = MakeObject<Presentation>();
//Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
//Προσθήκη νέου κανόνα στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
```

## Δείτε επίσης

* Τύπος ορισμού [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontFallBackRule](../../ifontfallbackrule/)
* Κλάση [IFontFallBackRulesCollection](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)