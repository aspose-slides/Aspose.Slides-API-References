---
title: MakeConstRef
second_title: Aspose.Slides für C++ API-Referenz
description: Trait, um einen generischen Typ \"const reference\" zu erzeugen, wenn er String oder ein SmartPtr<>-Typ ist.
type: docs
weight: 1769
url: /de/system/makeconstref/
---
## MakeConstRef struct


Trait, um einen generischen Typ \"const reference\" zu erzeugen, wenn er [String](../string/) oder ein SmartPtr<>-Typ ist.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Siehe auch

* Namensraum [System](../)
* Bibliothek [Aspose.Slides](../../)