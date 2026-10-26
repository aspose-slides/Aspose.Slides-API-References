---
title: end()
second_title: Aspose.Slides για το C++ API Reference
description: Πρόσβαση στη μέθοδο end() μιας υποκείμενης συλλογής. Συγκομπιλίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο end().
type: docs
weight: 391
url: /el/system/smartptr/end/
---
## SmartPtr::end() μέθοδος

Πρόσβαση στη μέθοδο [end()](./) μιας υποκείμενης συλλογής. Συγκομπιλίζεται μόνο εάν το SmartPtr_ είναι τύπος ειδίκευσης με τη μέθοδο [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### Τιμή Επιστροφής

επαναλήπτης στο τέλος της συλλογής

## SmartPtr::end() const μέθοδος

Πρόσβαση στη μέθοδο [end()](./) μιας υποκείμενης συλλογής. Συγκομπιλίζεται μόνο εάν το SmartPtr_ είναι τύπος ειδίκευσης με τη μέθοδο [end()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### Τιμή Επιστροφής

επαναλήπτης στο τέλος της συλλογής

## Δείτε επίσης

* Κλάση [SmartPtr](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)