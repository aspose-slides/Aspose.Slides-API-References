---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides για την Αναφορά API C++
description: Αντιπροσωπεύει τη συλλογή χρηστών των κανόνων FontFallBack για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Διαβάστε IFontFallBackRulesCollection.
type: docs
weight: 27
url: /el/aspose.slides/ifontsmanager/get_fontfallbackrulescollection/
---
## IFontsManager::get_FontFallBackRulesCollection() μέθοδος

Represents a user's collection of FontFallBack rules for managing of collections of fonts for proper substitutions by fallback functionality Διαβάστε [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual System::SharedPtr<IFontFallBackRulesCollection> Aspose::Slides::IFontsManager::get_FontFallBackRulesCollection()=0
```

## Παρατηρήσεις

```cpp
auto pres = MakeObject<Presentation>();
// Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Προσθήκη κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ή
// Αρχικοποίηση νέου αντικειμένου συλλογής κανόνων
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Προσθήκη κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// και αντικατάσταση της υπάρχουσας συλλογής με τη νέα στο FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Κλάση [IFontsManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)