---
title: AddFallBackFonts()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών FallBack.
type: docs
weight: 79
url: /el/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) μέθοδος

Προσθέτει νέα γραμματοσειρά(ες) στη λίστα των γραμματοσειρών FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Όνομα ή ονόματα γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |
## Παρατηρήσεις

```cpp
// Δημιουργία νέας παρουσίας FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Προσθήκη δεύτερης γραμματοσειράς στον κανόνα
newRule->AddFallBackFonts(u"MS Gothic");
//Προσθήκη τρίτης και τέταρτης γραμματοσειράς στον κανόνα
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) μέθοδος

Προσθέτει νέες γραμματοσειρές στη λίστα των γραμματοσειρών FallBack.

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Όνομα ή ονόματα γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |
## Παρατηρήσεις

```cpp
//Δημιουργία νέας παρουσίας FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Προσθήκη άλλων τριών γραμματοσειρών στον κανόνα
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [FontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)