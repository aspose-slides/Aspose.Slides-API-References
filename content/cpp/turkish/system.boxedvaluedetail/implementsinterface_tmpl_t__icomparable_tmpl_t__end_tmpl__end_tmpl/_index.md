---
title: ImplementsInterface< T, IComparable< T > >
second_title: Aspose.Slides C++ API Referansı
description: Kutuya alınmış nesnenin IComparable arayüzünü kendi başına uygulayıp uygulamaması gerektiğini kontrol eden şablon öncüsü.
type: docs
weight: 53
url: /tr/system.boxedvaluedetail/implementsinterface_tmpl_t__icomparable_tmpl_t__end_tmpl__end_tmpl/
---
## ImplementsInterface< T, IComparable< T > > struct


Şablon öncüsü, kutulanmış nesnenin [IComparable](../../system/icomparable/) arayüzünü kendi başına uygulayıp uygulaması gerektiğini kontrol eder.

```cpp
template<typename T>class ImplementsInterface< T, IComparable< T > > : public std::integral_constant<bool, std::is_arithmetic<T>::value||std::is_enum<T>::value>
```

## İlgili

* Ad alanı [System::BoxedValueDetail](../)
* Kütüphane [Aspose.Slides](../../)