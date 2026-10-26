---
title: ArrayInitializerCast()
second_title: Aspose.Slides για την Αναφορά API C++
description: Μετατρέπει τις βασικές τιμές του πίνακα (που το C# κάνει αυτόματα αλλά το C++ προφανώς δεν το κάνει).
type: docs
weight: 209
url: /el/system/objectext/arrayinitializercast/
---
## ObjectExt::ArrayInitializerCast(From ...) μέθοδος

Μετατρέπει τις βασικές τιμές του πίνακα (που το C# κάνει αυτόματα, αλλά το C++ προφανώς δεν το κάνει).

```cpp
template<typename To,typename ...> static std::enable_if<(std::is_fundamental<To>::value), std::array<To, sizeof...(From)>>::type System::ObjectExt::ArrayInitializerCast(From ...args)
```

### Παράμετροι προτύπου

| Parameter | Description |
| --- | --- |
| To | Τύπος προορισμού. |
| From | Τύποι προέλευσης. |

### Ορίσματα

| Parameter | Type | Description |
| --- | --- | --- |
| args | From ... | Τιμές προς μετατροπή και προσθήκη στον πίνακα προορισμού. |

### Τιμή επιστροφής

[Array](../../array/) που περιέχει μετατρεπόμενα αντίγραφα όλων των ορισμάτων με την ίδια σειρά.

## Δείτε επίσης

* Κλάση [ObjectExt](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)