---
title: ToArray()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις FallBack γραμματοσειρές για αυτόν τον κανόνα.
type: docs
weight: 144
url: /el/aspose.slides/fontfallbackrule/toarray/
---
## FontFallBackRule::ToArray() μέθοδος

Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές fallback για αυτόν τον κανόνα.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray() override
```

### Τιμή Επιστροφής

Πίνακας των [System::String](../../../system/string/)
## Παρατηρήσεις

```cpp
// Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Λάβετε όλα τα ονόματα γραμματοσειρών ως πίνακα.
ArrayPtr<String> fontNames = newRule->ToArray();
```

## FontFallBackRule::ToArray(int32_t, int32_t) μέθοδος

Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές fallback από το καθορισμένο εύρος στη λίστα.

```cpp
System::ArrayPtr<System::String> Aspose::Slides::FontFallBackRule::ToArray(int32_t startIndex, int32_t count) override
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | **int32_t** | Δείκτης του πρώτου γραμματοτύπου προς προσθήκη. |
| count | **int32_t** | Αριθμός γραμματοτύπων προς προσθήκη. |

### Τιμή Επιστροφής

Πίνακας των [System::String](../../../system/string/)
## Παρατηρήσεις

```cpp
// Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Λάβετε τα δύο τελευταία ονόματα γραμματοσειρών ως πίνακα.
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```

## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [FontFallBackRule](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)