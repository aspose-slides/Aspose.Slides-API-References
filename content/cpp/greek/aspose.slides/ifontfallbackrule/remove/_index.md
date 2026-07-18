---
title: Remove()
second_title: Aspose.Slides για την Αναφορά API C++
description: Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα.
type: docs
weight: 79
url: /el/aspose.slides/ifontfallbackrule/remove/
---
## IFontFallBackRule::Remove(System::String) μέθοδος


Αφαιρεί την πρώτη εμφάνιση μιας συγκεκριμένης γραμματοσειράς FallBack από τη λίστα.

```cpp
virtual void Aspose::Slides::IFontFallBackRule::Remove(System::String fontName)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Το όνομα της γραμματοσειράς που θα αφαιρεθεί από τη λίστα. |
## Σχόλια



```cpp
// Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Αφαίρεση του Tahoma από τη λίστα
newRule->Remove(u"Tahoma");
```


## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IFontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)