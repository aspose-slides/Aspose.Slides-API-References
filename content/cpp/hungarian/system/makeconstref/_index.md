---
title: MakeConstRef
second_title: Aspose.Slides a C++ API referenciája
description: Jellemző, amely általános típus \"const reference\"-t hoz létre, ha az String vagy egy SmartPtr<> típus.
type: docs
weight: 1769
url: /hu/system/makeconstref/
---
## MakeConstRef struct

Jellemző, amely általános típus "const reference"-t hoz létre, ha az [String](../string/) vagy egy SmartPtr<> típus.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Lásd még

* Névterület [System](../)
* Könyvtár [Aspose.Slides](../../)