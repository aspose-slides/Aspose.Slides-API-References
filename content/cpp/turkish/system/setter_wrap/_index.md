---
title: setter_wrap()
second_title: Aspose.Slides için C++ API Referansı
description: Tip dönüşümüyle statik ayarlayıcı işlevleri için aşırı yükleme.
type: docs
weight: 2822
url: /tr/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) fonksiyon


Tip dönüşümüyle statik ayarlayıcı işlevleri için aşırı yükleme.

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değer tipi. |
| T2 | Ayarlayıcı işlevi tarafından beklenen tip. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| pSetter | void(*)(T2) | Statik ayarlayıcı işlev referansı. |
| value | T | Ayarlanacak değer. |

### Dönüş Değeri

ayar değeri.

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) fonksiyon


Tip dönüşümüyle örnek ayarlayıcı işlevleri için aşırı yükleme.

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```


### Şablon parametreleri

| Parametre | Açıklama |
| --- | --- |
| T | Değer tipi. |
| T2 | Ayarlayıcı işlevi tarafından beklenen tip. |
| Host | Örnek tipi. |
| HostSet | - Özelliğin ayarlayıcısının tanımlandığı Host kendisi veya temel tipi. |

### Argümanlar

| Parametre | Tip | Açıklama |
| --- | --- | --- |
| host | Host *const | [Object](../object/) ayarlayıcı işlevi çağırmak için. |
| pSetter | void(HostSet::*)(T2) | Ayarlayıcı işlev referansı. |
| value | T | Ayarlanacak değer. |

### Dönüş Değeri

ayar değeri.

## Ayrıca Bakınız

* Ad alanı [System](../)
* Kütüphane [Aspose.Slides](../../)