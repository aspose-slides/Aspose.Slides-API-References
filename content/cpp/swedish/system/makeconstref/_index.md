---
title: MakeConstRef
second_title: Aspose.Slides för C++ API-referens
description: Egenskap för att göra en generisk typ \"const reference\" om det är String eller en SmartPtr<>-typ.
type: docs
weight: 1769
url: /sv/system/makeconstref/
---
## MakeConstRef struct

Egenskap för att göra en generisk typ "const reference" om den är [String](../string/) eller en SmartPtr<>-typ.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Se också

* Namnrymd [System](../)
* Bibliotek [Aspose.Slides](../../)