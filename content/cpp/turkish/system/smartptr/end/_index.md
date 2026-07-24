---
title: end()
second_title: Aspose.Slides for C++ API Referansı
description: Alt bir koleksiyonun end() metoduna erişim. Yalnızca SmartPtr_ end() metoduna sahip bir özelleştirme türü ise derlenir.
type: docs
weight: 391
url: /tr/system/smartptr/end/
---
## SmartPtr::end() yöntemi

Bir alt koleksiyonun [end()](./) metoduna erişim. Yalnızca SmartPtr_ [end()](./) metoduna sahip bir özelleştirme türü ise derlenir.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() -> decltype(std::declval<Q>().end())
```

### Dönüş Değeri

koleksiyonun sonuna gösteren yineleyici

## SmartPtr::end() const yöntemi

Bir alt koleksiyonun [end()](./) metoduna erişim. Yalnızca SmartPtr_ [end()](./) metoduna sahip bir özelleştirme türü ise derlenir.

```cpp
template<typename Q> auto System::SmartPtr<T>::end() const -> decltype(std::declval<const Q>().end())
```

### Dönüş Değeri

koleksiyonun sonuna gösteren yineleyici

## Ayrıca Bakınız

* Sınıf [SmartPtr](../)
* AdAlanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)