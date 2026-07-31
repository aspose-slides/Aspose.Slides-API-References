---
title: MakeConstRef
second_title: Referensi API Aspose.Slides untuk C++
description: Trait untuk membuat tipe generik \"const reference\" jika itu String atau tipe SmartPtr<>.
type: docs
weight: 1769
url: /id/system/makeconstref/
---
## MakeConstRef struct

Trait untuk membuat "const reference" tipe generik jika itu [String](../string/) atau tipe SmartPtr<>.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Lihat Juga

* Namespace [System](../)
* Perpustakaan [Aspose.Slides](../../)