---
title: begin()
second_title: Aspose.Slides for C++ API Referansı
description: Alt koleksiyonun begin() yöntemine erişimci. Yalnızca SmartPtr_ begin() yöntemiyle özelleştirilmiş bir tip ise derlenir.
type: docs
weight: 378
url: /tr/system/smartptr/begin/
---
## SmartPtr::begin() method

Accessor for [begin()](./) yöntemine erişimci. Yalnızca SmartPtr_ [begin()](./) yöntemiyle özelleştirilmiş bir tip ise derlenir.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() -> decltype(std::declval<Q>().begin())
```

### Dönüş Değeri

koleksiyonun başlangıcına iterator

## SmartPtr::begin() const method

Accessor for [begin()](./) yöntemine erişimci. Yalnızca SmartPtr_ [begin()](./) yöntemiyle özelleştirilmiş bir tip ise derlenir.

```cpp
template<typename Q> auto System::SmartPtr<T>::begin() const -> decltype(std::declval<const Q>().begin())
```

### Dönüş Değeri

koleksiyonun başlangıcına iterator

## Ayrıca Bakınız

* Sınıf [SmartPtr](../)
* Ad Alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)