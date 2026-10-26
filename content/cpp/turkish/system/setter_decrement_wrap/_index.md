---
title: setter_decrement_wrap()
second_title: Aspose.Slides for C++ API Referansı
description: Çevirmen, setter ve getter tanımlı sınıf özelliğine yönelik C# ön-azaltma ifadelerini bu fonksiyonun çağrısına dönüştürür.
type: docs
weight: 2861
url: /tr/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) fonksiyon


Çevirmen, setter ve getter tanımlı sınıfın özelliğine yönelik C# ön-azaltma ifadelerini bu fonksiyonun çağrısına dönüştürür.

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pGetter | T(*)() | Özelliğin getter serbest işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(*)(T) | Özelliğin setter serbest işlevine işaret eden fonksiyon işaretçisi |

### Dönüş Değeri

Azaltmadan önce özelliğin değeri

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) fonksiyon


Çevirmen, setter ve getter tanımlı nesnenin özelliğine yönelik C# ön-azaltma ifadelerini bu fonksiyonun (sabit olmayan getter için aşırı yük) çağrısına dönüştürür.

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin türü. |
| Host | - değiştirilmesi gereken örnek sınıfı |
| HostGet | - Host'un kendisi veya özelliğin getter'ının tanımlı olduğu temel tür |
| HostSet | - Host'un kendisi veya özelliğin setter'ının tanımlı olduğu temel tür |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | Host *const | Getter ve setter'ların çağrılacağı örnek. |
| pGetter | T(HostGet::*)() | Özelliğin getter işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(HostSet::*)(T) | Özelliğin setter işlevine işaret eden fonksiyon işaretçisi |

### Dönüş Değeri

Azaltmadan önce özelliğin değeri

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) fonksiyon


Çevirmen, setter ve getter tanımlı nesnenin özelliğine yönelik C# ön-azaltma ifadelerini bu fonksiyonun (sabit getter için aşırı yük) çağrısına dönüştürür.

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin türü. |
| Host | - değiştirilmesi gereken örnek sınıfı |
| HostConstGet | - Host'un kendisi veya özelliğin getter'ının tanımlı olduğu temel tür |
| HostSet | - Host'un kendisi veya özelliğin setter'ının tanımlı olduğu temel tür |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | Host *const | Getter ve setter'ların çağrılacağı örnek. |
| pGetter | T(HostConstGet::*)() const | Özelliğin getter işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(HostSet::*)(T) | Özelliğin setter işlevine işaret eden fonksiyon işaretçisi |

### Dönüş Değeri

Azaltmadan önce özelliğin değeri

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)