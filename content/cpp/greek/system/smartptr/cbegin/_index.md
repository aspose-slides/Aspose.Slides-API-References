---
title: cbegin()
second_title: Αναφορά API Aspose.Slides για C++
description: Πρόσβαση στη μέθοδο cbegin() μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν το SmartPtr_ είναι τύπος εξειδίκευσης με μέθοδο cbegin().
type: docs
weight: 404
url: /el/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const μέθοδος


Πρόσβαση στη μέθοδο [cbegin()](./) μιας υποκείμενης συλλογής. Μεταγλωττίζεται μόνο εάν SmartPtr_ είναι τύπος εξειδίκευσης με μέθοδο [cbegin()](./).

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```

### Τιμή Επιστροφής

iterator στην αρχή της συλλογής

## Δείτε επίσης

* Κλάση [SmartPtr](../)
* Χώρος ονομάτων [System](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)