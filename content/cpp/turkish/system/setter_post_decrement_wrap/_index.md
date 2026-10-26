---
title: setter_post_decrement_wrap()
second_title: C++ için Aspose.Slides API Referansı
description: Çevirmen, setter ve getter tanımlı sınıf özelliğini hedefleyen C#'nin post-decrement ifadelerini bu fonksiyonun çağrısına dönüştürür.
type: docs
weight: 2874
url: /tr/system/setter_post_decrement_wrap/
---
## System::setter_post_decrement_wrap(T(*)(), void(*)(T)) fonksiyon

Çevirmen, setter ve getter tanımlı sınıf özelliğini hedefleyen C#'nin post-decrement ifadelerini bu fonksiyonun çağrısına dönüştürür.

```cpp
template<typename T> T System::setter_post_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pGetter | T(*)() | İşlev işaretçisi, özelliğin getter serbest fonksiyonuna işaret eder |
| pSetter | void(*)(T) | İşlev işaretçisi, özelliğin setter serbest fonksiyonuna işaret eder |

### Dönüş Değeri

Özelliğin artırmadan önceki değeri

## System::setter_post_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) fonksiyon

Çevirmen, setter ve getter tanımlı örnek özelliğini hedefleyen C#'nin post-decrement ifadelerini bu fonksiyonun çağrısına dönüştürür (const olmayan getter için aşırı yükleme).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin tipi. |
| Host | - değiştirilmesi gereken örneğin sınıfı |
| HostGet | - Host'un kendisi veya temel tipi, özelliğin getter'ının tanımlı olduğu |
| HostSet | - Host'un kendisi veya temel tipi, özelliğin setter'ının tanımlı olduğu |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | Host *const | Getter ve setter'ları çağırmak için örnek. |
| pGetter | T(HostGet::*)() | İşlev işaretçisi, özelliğin getter serbest fonksiyonuna işaret eder |
| pSetter | void(HostSet::*)(T) | İşlev işaretçisi, özelliğin setter serbest fonksiyonuna işaret eder |

### Dönüş Değeri

Özelliğin artırmadan önceki değeri

## System::setter_post_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) fonksiyon

Çevirmen, setter ve getter tanımlı örnek özelliğini hedefleyen C#'nin post-decrement ifadelerini bu fonksiyonun çağrısına dönüştürür (const getter için aşırı yükleme).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin tipi. |
| Host | - değiştirilmesi gereken örneğin sınıfı |
| HostConstGet | - Host'un kendisi veya temel tipi, özelliğin getter'ının tanımlı olduğu |
| HostSet | - Host'un kendisi veya temel tipi, özelliğin setter'ının tanımlı olduğu |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | Host *const | Getter ve setter'ları çağırmak için örnek. |
| pGetter | T(HostConstGet::*)() const | İşlev işaretçisi, özelliğin getter fonksiyonuna işaret eder |
| pSetter | void(HostSet::*)(T) | İşlev işaretçisi, özelliğin setter serbest fonksiyonuna işaret eder |

### Dönüş Değeri

Özelliğin artırmadan önceki değeri

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)