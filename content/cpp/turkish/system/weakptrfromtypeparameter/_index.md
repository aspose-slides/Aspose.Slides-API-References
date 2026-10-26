---
title: WeakPtrFromTypeParameter
second_title: Aspose.Slides for C++ API Referansı
description: Argüman tipini, eğer bir gösterici tipi ise, zayıf göstericiye dönüştürmek için trait yapısı.
type: docs
weight: 2016
url: /tr/system/weakptrfromtypeparameter/
---
## WeakPtrFromTypeParameter struct


Argüman tipini zayıf göstericiye dönüştürmek için trait yapısı, eğer bir gösterici tipi ise.

```cpp
template<class T>class WeakPtrFromTypeParameter : public std::conditional<IsSmartPtr<T>::value, WeakPtr<RemoveShared<T>::type>, T>
```

## Ayrıca Bakınız

* İsim Uzayı [System](../)
* Kütüphane [Aspose.Slides](../../)