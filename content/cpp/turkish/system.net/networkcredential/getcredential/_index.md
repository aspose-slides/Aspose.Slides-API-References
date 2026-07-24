---
title: GetCredential()
second_title: Aspose.Slides C++ için API Referansı
description: Belirtilen URI ve kimlik doğrulama türü için kimlik bilgilerini döndürür.
type: docs
weight: 92
url: /tr/system.net/networkcredential/getcredential/
---
## NetworkCredential::GetCredential(System::SharedPtr\<Uri\>, String) method


Belirtilen URI ve kimlik doğrulama türü için kimlik bilgilerini döndürür.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(System::SharedPtr<Uri> uri, String authenticationType) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| uri | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI. |
| authenticationType | [String](../../../system/string/) | Kimlik doğrulama türü. |

## NetworkCredential::GetCredential(String, int32_t, String) method


Belirtilen ana bilgisayar adı, bağlantı noktası ve kimlik doğrulama türü için kimlik bilgilerini döndürür.

```cpp
System::SharedPtr<NetworkCredential> System::Net::NetworkCredential::GetCredential(String host, int32_t port, String authenticationType) override
```


### Argümanlar

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| host | [String](../../../system/string/) | Sunucu adı. |
| port | **int32_t** | Bağlantı noktası numarası. |
| authenticationType | [String](../../../system/string/) | Kimlik doğrulama türü. |

## Ayrıca Bakınız

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [NetworkCredential](../)
* Sınıf [Uri](../../../system/uri/)
* Sınıf [String](../../../system/string/)
* Ad alanı [System::Net](../../)
* Library [Aspose.Slides](../../../)