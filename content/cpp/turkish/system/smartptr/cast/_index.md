---
title: Cast()
second_title: Aspose.Slides için C++ API Referansı
description: İşaretçiyi kendi tipine dönüştürür.
type: docs
weight: 287
url: /tr/system/smartptr/cast/
---
## SmartPtr::Cast() const metot


İşaretçiyi kendi tipine dönüştürür.

```cpp
template<class Y,typename Check> std::enable_if_t<std::is_same<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Y | İşaret edilen nesnenin hedef tipi. |
| Check | Dönüştürme mümkün değilse istisna fırlatmak için bayraklar. |

### Dönüş Değeri

Her zaman paylaşımlı modda olan değiştirilmiş tipte işaretçi.

## SmartPtr::Cast() const metot


İşaretçiyi temel tipe static_cast kullanarak dönüştürür.

```cpp
template<class Y,typename Check> std::enable_if_t<!std::is_same<Y, T>::value &&std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Y | İşaret edilen nesnenin hedef tipi. |
| Check | Dönüştürme mümkün değilse istisna fırlatmak için bayraklar. |

### Dönüş Değeri

Her zaman paylaşımlı modda olan değiştirilmiş tipte işaretçi.

## SmartPtr::Cast() const metot


İşaretçiyi türetilmiş tipe dynamic_cast ile dönüştürür.

```cpp
template<class Y,typename Check> std::enable_if_t<Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Y | İşaret edilen nesnenin hedef tipi. |
| Check | Dönüştürme mümkün değilse istisna fırlatmak için bayraklar. |

### Dönüş Değeri

Her zaman paylaşımlı modda olan değiştirilmiş tipte işaretçi. Dönüşüm bulunamazsa InvalidCastException istisnası fırlatır.

## SmartPtr::Cast() const metot


İşaretçiyi türetilmiş tipe dynamic_cast ile dönüştürür.

```cpp
template<class Y,typename Check> std::enable_if_t<!Check::value &&!std::is_same<Y, T>::value &&!std::is_base_of<Y, T>::value, SmartPtr<Y>> System::SmartPtr<T>::Cast() const
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| Y | İşaret edilen nesnenin hedef tipi. |
| Check | Dönüştürme mümkün değilse istisna fırlatmak için bayraklar. |

### Dönüş Değeri

Her zaman paylaşımlı modda olan değiştirilmiş tipte işaretçi. Dönüşüm bulunamazsa nullptr döndürür.

## Ayrıca Bakınız

* Sınıf [SmartPtr](../)
* Ad alanı [System](../../)
* Kütüphane [Aspose.Slides](../../../)