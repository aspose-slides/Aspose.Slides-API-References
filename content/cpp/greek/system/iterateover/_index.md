---
title: IterateOver()
second_title: Aspose.Slides για C++ – Αναφορά API
description: "Αυτή η ιδιότητα συνάρτησης τυλίγει αντικείμενο enumerable (ή iterable) ώστε να μπορεί να χρησιμοποιηθεί με βρόχο range-based for. Αυτή η υπερφόρτωση για Enumerable χωρίς μεθόδους begin(), end() με όρισμα τύπου στόχου για (auto& value : IterateOver<SomeType>(enumerable))"
type: docs
weight: 2432
url: /el/system/iterateover/
---
## System::IterateOver(System::SmartPtr\<Enumerable\>) συνάρτηση

Αυτή η ιδιότητα συνάρτησης τυλίγει αντικείμενο enumerable (ή iterable) ώστε να μπορεί να χρησιμοποιηθεί με βρόχο range-based for. Αυτή η υπερφόρτωση για Enumerable χωρίς μεθόδους begin(), end() με όρισμα τύπου στόχου για (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος στόχου, πρέπει να επιστραφτεί από τον iterator |
| Enumerable | Ο τύπος του τυλιγμένου αντικειμένου |

## System::IterateOver(System::SmartPtr\<Enumerable\>) συνάρτηση

Αυτή η ιδιότητα συνάρτησης τυλίγει αντικείμενο enumerable (ή iterable) ώστε να μπορεί να χρησιμοποιηθεί με βρόχο range-based for. Αυτή η υπερφόρτωση για Enumerable χωρίς μεθόδους begin(), end() με προεπιλεγμένο όρισμα τύπου στόχου για (auto& value : IterateOver(enumerable)) ανάλογη με τον ακόλουθο κώδικα C# foreach (var value in enumerable)

```cpp
template<typename Enumerable> std::enable_if_t<!Details::IsIterable<Enumerable>::value, Details::EnumeratorAdapter<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Enumerable | Ο τύπος του τυλιγμένου αντικειμένου |

## System::IterateOver(System::SmartPtr\<Enumerable\>) συνάρτηση

Αυτή η ιδιότητα συνάρτησης τυλίγει αντικείμενο enumerable (ή iterable) ώστε να μπορεί να χρησιμοποιηθεί με βρόχο range-based for. Αυτή η υπερφόρτωση για Enumerable με μεθόδους begin(), end() με προεπιλεγμένο όρισμα τύπου στόχου για (auto& value : IterateOver(enumerable))

```cpp
template<typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Enumerable | Ο τύπος του τυλιγμένου αντικειμένου |

## System::IterateOver(System::SmartPtr\<Enumerable\>) συνάρτηση

Αυτή η ιδιότητα συνάρτησης τυλίγει αντικείμενο enumerable (ή iterable) ώστε να μπορεί να χρησιμοποιηθεί με βρόχο range-based for. Αυτή η υπερφόρτωση για Enumerable με μεθόδους begin(), end() με τύπο στόχου ίδιος με το αρχικό value_type του iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, System::SmartPtr<Enumerable>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Enumerable | Ο τύπος του τυλιγμένου αντικειμένου |
| T | Ο τύπος στόχου που πρέπει να επιστραφτεί από τον iterator |

## System::IterateOver(System::SmartPtr\<Enumerable\>) συνάρτηση

Αυτή η ιδιότητα συνάρτησης τυλίγει αντικείμενο enumerable (ή iterable) ώστε να μπορεί να χρησιμοποιηθεί με βρόχο range-based for. Αυτή η υπερφόρτωση για Enumerable με μεθόδους begin(), end() με διαφορετικό τύπο στόχου και το αρχικό value_type του iterator.

```cpp
template<typename T,typename Enumerable> std::enable_if_t<Details::IsIterable<Enumerable>::value &&!std::is_same<typename Details::ReturnTypeTrait<T>::ReturnType, Details::IterableValueType<Enumerable>>::value, Details::CppIteratorAdapter<Enumerable, T>> System::IterateOver(System::SmartPtr<Enumerable> enumerable)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Enumerable | Ο τύπος του τυλιγμένου αντικειμένου |
| T | Ο τύπος στόχου που πρέπει να επιστραφτεί από τον iterator |

## System::IterateOver(const Enumerable *) συνάρτηση

Αυτή η ιδιότητα συνάρτησης τυλίγει αντικείμενο enumerable (ή iterable) ώστε να μπορεί να χρησιμοποιηθεί με βρόχο range-based for. Αυτή η υπερφόρτωση για Enumerable αυτή με προεπιλεγμένο τύπο στόχου.

```cpp
template<typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, Details::ValueTypeOfEnumerable<Enumerable>, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| Enumerable | Ο τύπος του τυλιγμένου αντικειμένου |

## System::IterateOver(const Enumerable *) συνάρτηση

Αυτή η ιδιότητα συνάρτησης τυλίγει αντικείμενο enumerable (ή iterable) ώστε να μπορεί να χρησιμοποιηθεί με βρόχο range-based for. Αυτή η υπερφόρτωση για Enumerable χωρίς μεθόδους begin(), end() με όρισμα τύπου στόχου για (auto& value : IterateOver<SomeType>(enumerable))

```cpp
template<typename T,typename Enumerable> std::enable_if_t<!IsSmartPtr<Enumerable>::value, Details::EnumeratorAdapter<Enumerable, T, Enumerable *>> System::IterateOver(const Enumerable *enumerable)
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος στόχου, πρέπει να επιστραφτεί από τον iterator |
| Enumerable | Ο τύπος του τυλιγμένου αντικειμένου |

## Δείτε επίσης

* Κλάση [SmartPtr](../smartptr/)
* Δομή [IsSmartPtr](../issmartptr/)
* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)