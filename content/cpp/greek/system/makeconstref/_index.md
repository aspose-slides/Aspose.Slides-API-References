---
title: MakeConstRef
second_title: Aspose.Slides για C++ API Αναφορά
description: Ιδιότητα για τη δημιουργία του γενικού τύπου \"const reference\" εάν είναι String ή τύπος SmartPtr<>.
type: docs
weight: 1743
url: /el/system/makeconstref/
---
## MakeConstRef struct

Ιδιότητα για τη δημιουργία του \"const reference\" γενικού τύπου εάν είναι [String](../string/) ή τύπου SmartPtr<>.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Δείτε επίσης

* Χώρος ονομάτων [System](../)
* Βιβλιοθήκη [Aspose.Slides](../../)