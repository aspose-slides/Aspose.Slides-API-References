---
title: GetSubstitutions()
second_title: Αναφορά API Aspose.Slides για C++
description: Λαμβάνει τις πληροφορίες σχετικά με τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης.
type: docs
weight: 66
url: /el/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() μέθοδος

Λαμβάνει τις πληροφορίες σχετικά με τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση της παρουσίασης.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```

### Τιμή Επιστροφής

Συλλογή όλων των αντικαταστάσεων γραμματοσειρών [FontSubstitutionInfo](../../fontsubstitutioninfo/).

## Παρατηρήσεις

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) μέθοδος

Λαμβάνει τις πληροφορίες σχετικά με τις γραμματοσειρές που θα αντικατασταθούν κατά την απόδοση των καθορισμένων διαφανειών.

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | Ένας πίνακας από ευρετήρια διαφανειών για τα οποία θα ληφθούν πληροφορίες αντικατάστασης γραμματοσειρών, ξεκινώντας από το 1. |

### Τιμή Επιστροφής

Μια συλλογή όλων των αντικαταστάσεων γραμματοσειρών ([FontSubstitutionInfo](../../fontsubstitutioninfo/)) για τις καθορισμένες διαφάνειες.

## Παρατηρήσεις

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [IEnumerable](../../../system.collections.generic/ienumerable/)
* Κλάση [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* Κλάση [IFontsManager](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)