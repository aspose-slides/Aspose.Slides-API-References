---
title: get_FontFallBackRulesCollection()
second_title: Aspose.Slides για την Αναφορά API του C++
description: Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για τις σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Διαβάστε IFontFallBackRulesCollection.
type: docs
weight: 27
url: /el/aspose.slides/fontsmanager/get_fontfallbackrulescollection/
---
## FontsManager::get_FontFallBackRulesCollection() μέθοδος


Αντιπροσωπεύει τη συλλογή κανόνων FontFallBack ενός χρήστη για τη διαχείριση συλλογών γραμματοσειρών για τις σωστές αντικαταστάσεις μέσω της λειτουργίας fallback. Διαβάστε [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/).

```cpp
System::SharedPtr<Aspose::Slides::IFontFallBackRulesCollection> Aspose::Slides::FontsManager::get_FontFallBackRulesCollection() override
```

## Παρατηρήσεις



```cpp
auto pres = MakeObject<Presentation>();
// Λήψη κενής ή προαρχικοποιημένης συλλογής κανόνων από το FontsManager
auto rulesList = pres->get_FontsManager()->get_FontFallBackRulesCollection();
// Προσθήκη κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// ή
// Αρχικοποίηση νέας παρουσίας συλλογής κανόνων
auto rulesList = MakeObject<FontFallBackRulesCollection>();
// Προσθήκη κανόνων στη συλλογή
rulesList->Add(MakeObject<FontFallBackRule>(0x400, 0x4FF, u"Times New Roman"));
// και αντικατάσταση της υπάρχουσας συλλογής με τη νέα στο FontsManager
pres->get_FontsManager()->set_FontFallBackRulesCollection(rulesList);
```

## Δείτε επίσης

* Τύπος [SharedPtr](../../../system/sharedptr/)
* Κλάση [IFontFallBackRulesCollection](../../ifontfallbackrulescollection/)
* Κλάση [FontsManager](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)