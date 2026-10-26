---
title: IndexOf()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει έναν δείκτη του καθορισμένου κανόνα στη συλλογή.
type: docs
weight: 157
url: /el/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) μέθοδος

Επιστρέφει έναν δείκτη του συγκεκριμένου κανόνα στη συλλογή.

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Όνομα γραμματοσειράς προς εύρεση. |

### Τιμή Επιστροφής

Δείκτης μιας γραμματοσειράς ή -1 εάν η γραμματοσειρά δεν βρεθεί στη λίστα.

## Σχόλια

```cpp
// Δημιουργεί έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Παίρνει το δείκτη του Tahoma.
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [FontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)