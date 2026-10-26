---
title: GetCredential()
second_title: Aspose.Slides for C++ API Referansı
description: Belirtilen URI ön eki ve kimlik doğrulama türü için kimlik bilgilerini döndürür.
type: docs
weight: 66
url: /tr/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) metod

Belirtilen URI ön ekine ve kimlik doğrulama türüne ait kimlik bilgilerini döndürür.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI ön eki. |
| authenticationType | [String](../../../system/string/) | Kimlik doğrulama türü. |

## CredentialCache::GetCredential(String, int32_t, String) metod

Belirtilen ana bilgisayar adı, bağlantı noktası ve kimlik doğrulama türüne ait kimlik bilgilerini döndürür.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | [String](../../../system/string/) | Kimlik bilgileriyle ilişkili ana bilgisayar adı. |
| port | **int32_t** | Bağlantı noktası numarası. |
| authenticationType | [String](../../../system/string/) | Kimlik doğrulama türü. |

## Ayrıca

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [NetworkCredential](../../networkcredential/)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Sınıf [CredentialCache](../)
* Ad alanı [System::Net](../../)
* Kütüphane [Aspose.Slides](../../../)