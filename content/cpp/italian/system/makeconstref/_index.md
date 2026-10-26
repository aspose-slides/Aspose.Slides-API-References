---
title: MakeConstRef
second_title: Riferimento API di Aspose.Slides per C++
description: Trait per creare un tipo generico \"const reference\" se è String o un tipo SmartPtr<>.
type: docs
weight: 1769
url: /it/system/makeconstref/
---
## MakeConstRef struct


Trait per creare un \"const reference\" di tipo generico se è [String](../string/) o un tipo SmartPtr<>.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Vedi anche

* Namespace [System](../)
* Libreria [Aspose.Slides](../../)