---
title: IsCppContainer
second_title: Aspose.Slides για C++ API Αναφορά
description: "Ελέγχει εάν ένας συγκεκριμένος τύπος είναι κοντέινερ τύπου STL. Για το σκοπό αυτό, ελέγχει την ύπαρξη των τύπων μέλους iterator και const_iterator. Εάν και οι δύο υπάρχουν, κληρονομεί το std::true_type, διαφορετικά κληρονομεί το std::false_type."
type: docs
weight: 40
url: /el/system.testpredicates.typetraits/iscppcontainer/
---
## IsCppContainer struct

Ελέγχει εάν ένας συγκεκριμένος τύπος είναι κοντέινερ τύπου STL. Για το σκοπό αυτό, ελέγχει την ύπαρξη των τύπων μέλους iterator και const_iterator. Εάν και οι δύο υπάρχουν, κληρονομεί το std::true_type, διαφορετικά κληρονομεί το std::false_type.

```cpp
template<typename T,typename Enable>class IsCppContainer : public std::false_type
```

### Παράμετροι προτύπου

| Παράμετρος | Περιγραφή |
| --- | --- |
| T | Τύπος προς έλεγχο. |
| Enable | Τυπικό όρισμα για τη λειτουργία του SFINAE. |

## Δείτε επίσης

* Χώρος ονομάτων [System::TestPredicates::TypeTraits](../)
* Βιβλιοθήκη [Aspose.Slides](../../)