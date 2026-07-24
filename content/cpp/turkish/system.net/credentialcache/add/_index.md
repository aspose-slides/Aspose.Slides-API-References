---
title: Add()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen ağ kimlik bilgilerini önbelleğe ekler.
type: docs
weight: 40
url: /tr/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) metot

Belirtilen ağ kimlik bilgilerini önbelleğe ekler.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Kimlik bilgilerinin ilişkilendirildiği kaynağın URI öneki. |
| authenticationType | [String](../../../system/string/) | Kimlik doğrulama şeması. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Eklenecek kimlik bilgileri. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) metot

Belirtilen ağ kimlik bilgilerini önbelleğe ekler.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | [String](../../../system/string/) | Kimlik bilgilerinin ilişkilendirildiği ana bilgisayar adı. |
| port | **int32_t** | Bağlantı noktası numarası. |
| authenticationType | [String](../../../system/string/) | Kimlik doğrulama şeması. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Eklenecek kimlik bilgileri. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [NetworkCredential](../../networkcredential/)
* Sınıf [CredentialCache](../)
* Ad Alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)