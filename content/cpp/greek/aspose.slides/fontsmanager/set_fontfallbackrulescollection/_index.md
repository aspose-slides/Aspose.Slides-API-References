---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides για C++ - Αναφορά API
description: Αντιπροσωπεί τη συλλογή του χρήστη από κανόνες FontFallBack για τη διαχείριση συλλογών γραμματοσειρών ώστε να γίνονται σωστές αντικαταστάσεις μέσω λειτουργίας fallback. Γράψτε IFontFallBackRulesCollection.
type: docs
weight: 40
url: /el/aspose.slides/fontsmanager/set_fontfallbackrulescollection/
---
## FontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<Aspose::Slides::IFontFallBackRulesCollection\>) μέθοδος

Αντιπροσωπεί τη συλλογή του χρήστη από κανόνες FontFallBack για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω λειτουργίας fallback Γράψτε [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
void Aspose::Slides::FontsManager::set_FontFallBackRulesCollection(System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> value) override
```

## Παρατηρήσεις

```cpp
auto pres = MakeObject<Presentation>();
// Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// προσθήκη κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ή
// αρχικοποίηση νέου αντικειμένου της συλλογής κανόνων
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// προσθήκη κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// και αντικατάσταση της υπάρχουσας συλλογής με τη νέα στο FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Κλάση [FontsManager](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)