---
title: setter_increment_wrap()
second_title: Aspose.Slides for C++ API Referansı
description: Çevirmen, setter ve getter tanımlı sınıf özelliğini hedefleyen C#'s artırma ifadelerini bu işlevin çağrısına dönüştürür.
type: docs
weight: 2835
url: /tr/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) fonksiyon


Çevirmen, setter ve getter tanımlı sınıf özelliğine yönelik C# artırma ifadelerini bu işlevin çağrısına dönüştürür.

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin tipi |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pGetter | T(*)() | Özelliğin getter serbest işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(*)(T) | Özelliğin setter serbest işlevine işaret eden fonksiyon işaretçisi |

### Dönüş Değeri

Özelliğin artırılmış değeri

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) fonksiyon


Çevirmen, setter ve getter tanımlı sınıf özelliğine yönelik C# artırma ifadelerini bu işlevin çağrısına dönüştürür.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin tipi |
| Host | - sınıfı değiştirilmek istenen örnek |
| HostGet | - Host kendisi veya özelliğin getter'ının tanımlandığı temel tip |
| HostSet | - Host kendisi veya özelliğin setter'ının tanımlandığı temel tip |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | Host *const | Özelliği artırılacak nesneye gösteren gösterici |
| pGetter | T(HostGet::*)() | Özelliğin getter yöntemine işaret eden fonksiyon işaretçisi |
| pSetter | void(HostSet::*)(T) | Özelliğin setter yöntemine işaret eden fonksiyon işaretçisi |

### Dönüş Değeri

Özelliğin artırılmış değeri

## Ayrıca Bakınız

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)