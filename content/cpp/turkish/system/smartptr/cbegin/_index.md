---
title: cbegin()
second_title: Aspose.Slides for C++ API Referansı
description: Alt koleksiyonun cbegin() metoduna erişimci. Yalnızca SmartPtr_ cbegin() metoduna sahip bir özelleştirme türü ise derlenir.
type: docs
weight: 404
url: /tr/system/smartptr/cbegin/
---
## SmartPtr::cbegin() const metodu


[cbegin()](./) metoduna bir alt koleksiyonun erişimcisi. Yalnızca SmartPtr_ [cbegin()](./) metoduna sahip bir özelleştirme türü ise derlenir.

```cpp
template<typename Q> auto System::SmartPtr<T>::cbegin() const -> decltype(std::declval<const Q>().cbegin())
```


### Dönüş Değeri

koleksiyonun başına bir yineleyici

## Ayrıca Bakınız

* Sınıf [SmartPtr](../)
* Ad Alanı [System](../../)
* Library [Aspose.Slides](../../../)