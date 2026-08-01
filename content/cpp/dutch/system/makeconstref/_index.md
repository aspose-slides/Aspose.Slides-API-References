---
title: MakeConstRef
second_title: Aspose.Slides voor C++ API-referentie
description: Trait om een generiek type \"const reference\" te maken als het String of een SmartPtr<> type is.
type: docs
weight: 1769
url: /nl/system/makeconstref/
---
## MakeConstRef struct

Trait om een generiek type \"const reference\" te maken als het [String](../string/) of een SmartPtr<> type is.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Zie ook

* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)