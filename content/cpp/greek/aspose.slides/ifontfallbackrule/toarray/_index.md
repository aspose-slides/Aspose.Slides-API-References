---
title: ToArray()
second_title: Aspose.Slides για C++ Αναφορά API
description: Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack για αυτόν τον κανόνα.
type: docs
weight: 105
url: /el/aspose.slides/ifontfallbackrule/toarray/
---
## IFontFallBackRule::ToArray() method


Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack για αυτόν τον κανόνα.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray()=0
```


### Τιμή Επιστροφής

Πίνακας του [System::String](../../../system/string/)
## Παρατηρήσεις



```cpp
// Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Λάβετε όλα τα ονόματα γραμματοσειρών ως πίνακα
ArrayPtr<String> fontNames = newRule->ToArray();
```


## IFontFallBackRule::ToArray(int32_t, int32_t) method


Δημιουργεί και επιστρέφει έναν πίνακα με όλες τις γραμματοσειρές FallBack από το καθορισμένο εύρος στη λίστα.

```cpp
virtual System::ArrayPtr<System::String> Aspose::Slides::IFontFallBackRule::ToArray(int32_t startIndex, int32_t count)=0
```


### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| startIndex | **int32_t** | Δείκτης της πρώτης γραμματοσειράς προς προσθήκη. |
| count | **int32_t** | Αριθμός γραμματοσειρών προς προσθήκη. |

### Τιμή Επιστροφής

Πίνακας του [System::String](../../../system/string/)
## Παρατηρήσεις



```cpp
// Δημιουργήστε έναν κανόνα που περιέχει μια λίστα γραμματοσειρών.
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
//Λάβετε τα τελευταία δύο ονόματα γραμματοσειρών ως πίνακα
ArrayPtr<String> fontNames = newRule->ToArray(2, 2);
```


## Δείτε επίσης

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Κλάση [String](../../../system/string/)
* Κλάση [IFontFallBackRule](../)
* Ονομαχώρος [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)