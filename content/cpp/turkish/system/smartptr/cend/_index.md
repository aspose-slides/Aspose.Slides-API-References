---
title: cend()
second_title: Aspose.Slides için C++ API Referansı
description: Altındaki bir koleksiyonun cend() metoduna erişimci. Yalnızca SmartPtr_ cend() metoduna sahip bir özelleştirme türü ise derlenir.
type: docs
weight: 417
url: /tr/system/smartptr/cend/
---
## SmartPtr::cend() const metodu

Altındaki koleksiyonun [cend()](./) metoduna erişimci. Yalnızca SmartPtr_ [cend()](./) metoduna sahip bir özelleştirme türü ise derlenir.

```cpp
template<typename Q> auto System::SmartPtr<T>::cend() const -> decltype(std::declval<const Q>().cend())
```

### Dönüş Değeri

koleksiyonun sonuna bir iterator

## Ayrıca

* Sınıf [SmartPtr](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)