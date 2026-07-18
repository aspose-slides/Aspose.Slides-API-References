---
title: ObjectType
second_title: Aspose.Slides για C++ Αναφορά API
description: Παρέχει στατικές μεθόδους που υλοποιούν getters τύπου αντικειμένου. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες εμφώλευσης. Δεν πρέπει ποτέ να δημιουργείτε αντικείμενα αυτού με κανένα τρόπο.
type: docs
weight: 1145
url: /el/system/objecttype/
---
## ObjectType κλάση

Παρέχει στατικές μεθόδους που υλοποιούν getters τύπου αντικειμένου. Αυτός είναι ένας στατικός τύπος χωρίς υπηρεσίες εμφώλευσης. Δεν πρέπει ποτέ να δημιουργείτε αντικείμενα αυτού με κανένα τρόπο.

```cpp
class ObjectType
```

## Μέθοδοι

| Μέθοδος | Περιγραφή |
| --- | --- |
| static std::enable_if\<[IsSmartPtr](../issmartptr/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για έξυπρους δείκτες. |
| static std::enable_if<\![IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value\&&\![IsSmartPtr](../issmartptr/)\<T\>::value\&&\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για δομές. |
| static std::enable_if\<[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T\&) | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για εξαιρέσεις. |
| static std::enable_if\<std::is_fundamental\<T\>::value||std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για βασικούς τύπους. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)(const T) | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για [Nullable](../nullable/) τύπους. |
| static std::enable_if\<std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για βασικούς τύπους. |
| static std::enable_if\<std::is_enum\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για τύπους enum. |
| static std::enable_if<(\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&\![IsBoxable](../isboxable/)\<T\>::value)||[IsExceptionWrapper](../isexceptionwrapper/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για δομές και δείκτες. |
| static std::enable_if\<[IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για [Nullable](../nullable/). |
| static std::enable_if\<detail::is_a\<T, MulticastDelegate\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για MulticastDelegate. |
| static std::enable_if<\!std::is_fundamental\<T\>::value\&&\!std::is_enum\<T\>::value\&&[IsBoxable](../isboxable/)\<T\>::value\&&\!detail::is_a\<T, MulticastDelegate\>::value\&&\![IsNullable](../isnullable/)\<T\>::value, constSystem::TypeInfo\&\>::type [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για δομές και δείκτες. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)(const [String](../string/)\&) | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για τύπο string. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |
| static const [System::TypeInfo](../typeinfo/)\& [GetType](./gettype/)() | Υλοποιεί τη μετάφραση του typeof(). Υπερφόρτωση για **uint8_t**. |

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)