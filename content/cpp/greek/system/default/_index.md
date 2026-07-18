---
title: Default()
second_title: Aspose.Slides για C++ Αναφορά API
description: Επιστρέφει την αναφορά στη μοναδική προεπιλεγμένη κατασκευασμένη παρουσία του τύπου εξαίρεσης.
type: docs
weight: 2198
url: /el/system/default/
---
## System::Default() συνάρτηση


Επιστρέφει την αναφορά στη μοναδική προεπιλεγμένη κατασκευασμένη παρουσία του τύπου εξαίρεσης.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος του οποίου επιστρέφεται η παρουσία |

## System::Default() συνάρτηση


Επιστρέφει την αναφορά στη μοναδική προεπιλεγμένη κατασκευασμένη παρουσία του μη-εξαίρεσης τύπου.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```


### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Ο τύπος του οποίου επιστρέφεται η παρουσία |

## Δείτε επίσης

* Struct [IsExceptionWrapper](../isexceptionwrapper/)
* Namespace [System](../)
* Library [Aspose.Slides](../../)