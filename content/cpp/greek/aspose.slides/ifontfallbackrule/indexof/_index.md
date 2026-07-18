---
title: IndexOf()
second_title: Αναφορά API του Aspose.Slides για C++
description: Επιστρέφει έναν δείκτη του συγκεκριμένου κανόνα στη συλλογή.
type: docs
weight: 118
url: /el/aspose.slides/ifontfallbackrule/indexof/
---
## IFontFallBackRule::IndexOf(System::String) μέθοδος

Επιστρέφει έναν δείκτη του συγκεκριμένου κανόνα στη συλλογή.

```cpp
virtual int32_t Aspose::Slides::IFontFallBackRule::IndexOf(System::String fontName)=0
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | Το όνομα της γραμματοσειράς για εύρεση. |

### Τιμή επιστροφής

Δείκτης μιας γραμματοσειράς ή -1 αν η γραμματοσειρά δεν βρεθεί στη λίστα.
## Παρατηρήσεις

```cpp
// Δημιουργεί έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Λαμβάνει δείκτη του Tahoma
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```

## Δείτε επίσης

* Κλάση [String](../../../system/string/)
* Κλάση [IFontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)