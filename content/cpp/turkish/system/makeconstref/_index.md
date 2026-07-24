---
title: MakeConstRef
second_title: Aspose.Slides for C++ API Referansı
description: String veya SmartPtr<> türündeyse, genel tür \"const reference\" oluşturmak için bir özellik.
type: docs
weight: 1769
url: /tr/system/makeconstref/
---
## MakeConstRef struct

Genel tür "const reference" oluşturmak için özellik, eğer [String](../string/) veya SmartPtr<> türü ise.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)