---
title: setter_post_increment_wrap()
second_title: Aspose.Slides için C++ API Referansı
description: Çevirmen, ayarlayıcı ve alıcı tanımlı sınıf özelliğini hedefleyen C#'ın post-increment ifadelerini bu işlevin çağrısına dönüştürür.
type: docs
weight: 2848
url: /tr/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) function

Çevirmen, ayarlayıcı ve alıcı tanımlı sınıf özelliğini hedefleyen C#'ın post-increment ifadelerini bu işlevin çağrısına dönüştürür.

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| pGetter | T(*)() | Özelliğin alıcı serbest işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(*)(T) | Özelliğin ayarlayıcı serbest işlevine işaret eden fonksiyon işaretçisi |

### Dönüş Değeri

Artırma işleminden önce özelliğin değeri

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) function

Çevirmen, ayarlayıcı ve alıcı tanımlı örnek özelliğini hedefleyen C#'ın post-increment ifadelerini bu işlevin çağrısına dönüştürür (sabit olmayan alıcı için aşırı yükleme).

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin türü. |
| Host | - değiştirilecek örnek sınıfı |
| HostGet | - Host kendisi veya özelliğin alıcısının tanımlı olduğu temel türü |
| HostSet | - Host kendisi veya özelliğin ayarlayıcısının tanımlı olduğu temel türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | Host *const | Alıcı ve ayarlayıcıların çağrılacağı örnek. |
| pGetter | T(HostGet::*)() | Özelliğin alıcı işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(HostSet::*)(T) | Özelliğin ayarlayıcı işlevine işaret eden fonksiyon işaretçisi |

### Dönüş Değeri

Artırma işleminden önce özelliğin değeri

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) function

Çevirmen, ayarlayıcı ve alıcı tanımlı örnek özelliğini hedefleyen C#'ın post-increment ifadelerini bu işlevin çağrısına dönüştürür (sabit alıcı için aşırı yükleme).

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```

### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Özelliğin türü. |
| Host | - değiştirilecek örnek sınıfı |
| HostConstGet | - Host kendisi veya özelliğin alıcısının tanımlı olduğu temel türü |
| HostSet | - Host kendisi veya özelliğin ayarlayıcısının tanımlı olduğu temel türü |

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | Host *const | Alıcı ve ayarlayıcıların çağrılacağı örnek. |
| pGetter | T(HostConstGet::*)() const | Özelliğin alıcı işlevine işaret eden fonksiyon işaretçisi |
| pSetter | void(HostSet::*)(T) | Özelliğin ayarlayıcı işlevine işaret eden fonksiyon işaretçisi |

### Dönüş Değeri

Artırma işleminden önce özelliğin değeri

## İlgili

* Ad Alanı [System](../)
* Kütüphane [Aspose.Slides](../../)