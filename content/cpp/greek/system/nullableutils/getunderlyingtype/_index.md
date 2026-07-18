---
title: GetUnderlyingType()
second_title: Αναφορά API Aspose.Slides για C++
description: Επιστρέφει το υποκείμενο type argument του nullable τύπου που ορίζεται.
type: docs
weight: 1
url: /el/system/nullableutils/getunderlyingtype/
---
## NullableUtils::GetUnderlyingType(const System::TypeInfo\&) μέθοδος

Επιστρέφει το εσωτερικό type argument του καθορισμένου nullable τύπου.

```cpp
static const System::TypeInfo & System::NullableUtils::GetUnderlyingType(const System::TypeInfo &nullableType)
```

### Παράμετροι

| Παράμετρος | Τύπος | Περιγραφή |
| --- | --- | --- |
| nullableType | const [System::TypeInfo](../../typeinfo/)\& | Ένα αντικείμενο System.Type που περιγράφει έναν κλειστό γενικό nullable τύπο. |

### Τιμή Επιστροφής

Το type argument της παραμέτρου nullableType, εάν η παράμετρος nullableType είναι ένας κλειστός γενικός nullable τύπος· διαφορετικά, null

## Δείτε επίσης

* Κλάση [TypeInfo](../../typeinfo/)
* Κλάση [NullableUtils](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)