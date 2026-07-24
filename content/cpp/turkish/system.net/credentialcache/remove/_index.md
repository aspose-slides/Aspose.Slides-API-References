---
title: Remove()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URI öneki ve kimlik doğrulama türü için ağ kimlik bilgilerini kaldırır.
type: docs
weight: 53
url: /tr/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) metot


Belirtilen URI öneki ve kimlik doğrulama türü için ağ kimlik bilgilerini kaldırır.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI öneki. |
| authenticationType | [String](../../../system/string/) | Kimlik doğrulama türü. |

## CredentialCache::Remove(String, int32_t, String) metot


Belirtilen ana bilgisayar adı, port ve kimlik doğrulama türü için ağ kimlik bilgilerini kaldırır.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | [String](../../../system/string/) | Kimlik bilgileriyle ilişkilendirilen ana bilgisayar adı. |
| port | **int32_t** | Port numarası. |
| authenticationType | [String](../../../system/string/) | Bir kimlik doğrulama türü. |

## İlgili

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)