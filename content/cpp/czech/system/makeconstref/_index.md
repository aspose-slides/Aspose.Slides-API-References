---
title: MakeConstRef
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Vlastnost pro vytvoření generického typu \"const reference\", pokud je String nebo typ SmartPtr<>.
type: docs
weight: 1769
url: /cs/system/makeconstref/
---
## MakeConstRef struktura

Vlastnost k vytvoření generického typu \"const reference\", pokud je [String](../string/) nebo typ SmartPtr<>.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Viz také

* jmenný prostor [System](../)
* knihovna [Aspose.Slides](../../)