---
title: Remove()
second_title: Aspose.Slides για C++ API Αναφορά
description: Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα.
type: docs
weight: 118
url: /el/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) μέθοδος


Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα.

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Το όνομα της γραμματοσειράς που θα αφαιρεθεί από τη λίστα. |
## Παρατηρήσεις



```cpp
// Δημιουργεί ένα κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Αφαιρεί το Tahoma από τη λίστα.
newRule->Remove(u"Tahoma");
```


## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [FontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)