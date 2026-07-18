---
title: set_FontFallBackRulesCollection()
second_title: Aspose.Slides για C++ Αναφορά API
description: Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Γράψτε IFontFallBackRulesCollection.
type: docs
weight: 40
url: /el/aspose.slides/ifontsmanager/set_fontfallbackrulescollection/
---
## IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr\<IFontFallBackRulesCollection\>) μέθοδος

Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Γράψτε [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
virtual void Aspose::Slides::IFontsManager::set_FontFallBackRulesCollection(System::SharedPtr<IFontFallBackRulesCollection> value)=0
```

## Σχόλια

```cpp
auto pres = MakeObject<Presentation>();
// Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// προσθήκη κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ή
// αρχικοποίηση νέας εμφάνισης της συλλογής κανόνων
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// προσθήκη κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// και αντικατάσταση της υπάρχουσας συλλογής με τη νέα στο FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Κλάση [IFontsManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)