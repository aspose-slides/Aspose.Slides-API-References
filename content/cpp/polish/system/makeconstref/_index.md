---
title: MakeConstRef
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Cecha umożliwiająca utworzenie generycznego typu \"const reference\", jeśli jest String lub typu SmartPtr<>.
type: docs
weight: 1769
url: /pl/system/makeconstref/
---
## MakeConstRef struct


Cecha umożliwiająca utworzenie generycznego typu \"referencja const\", jeśli jest [String](../string/) lub typu SmartPtr<>.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Zobacz także

* Namespace [System](../)
* Biblioteka [Aspose.Slides](../../)