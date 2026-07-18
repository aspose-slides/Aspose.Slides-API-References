---
title: AddFallBackFonts()
second_title: Aspose.Slides για C++ API Αναφορά
description: Προσθέτει μια νέα γραμματοσειρά(ές) στη λίστα των γραμματοσειρών FallBack.
type: docs
weight: 40
url: /el/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) μέθοδος

Προσθέτει μια νέα γραμματοσειρά(ές) στη λίστα των γραμματοσειρών FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Το όνομα ή τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |
## Παρατηρήσεις

```cpp
//Δημιουργία νέου αντικειμένου FantFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Προσθήκη δεύτερης γραμματοσειράς στον κανόνα
newRule->AddFallBackFonts(u"MS Gothic");
//Προσθήκη τρίτης και τέταρτης γραμματοσειρών στον κανόνα
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) μέθοδος

Προσθέτει νέες γραμματοσειρές στη λίστα των γραμματοσειρών FallBack.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Τα ονόματα της γραμματοσειράς (διαχωρισμένα με κόμμα) για FallBack |
## Παρατηρήσεις

```cpp
//Δημιουργία νέου αντικειμένου FontFallBackRule
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//Προσθήκη άλλων τριών γραμματοσειρών στον κανόνα
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [IFontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)