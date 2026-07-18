---
title: begin()
second_title: Αναφορά API Aspose.Slides για C++
description: Πρόσβαση στη μέθοδο begin() μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο begin().
type: docs
weight: 378
url: /el/system/smartptr/begin/
---
## SmartPtr::begin() μέθοδος

Πρόσβαση στη μέθοδο [begin()](./) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```

### Τιμή Επιστροφής

Δείκτης στην αρχή της συλλογής

## SmartPtr::begin() const μέθοδος

Πρόσβαση στη μέθοδο [begin()](./) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με τη μέθοδο [begin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```

### Τιμή Επιστροφής

Δείκτης στην αρχή της συλλογής

## Δείτε επίσης

* Κλάση [SmartPtr](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)