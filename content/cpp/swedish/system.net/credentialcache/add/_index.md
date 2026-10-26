---
title: Add()
second_title: Aspose.Slides för C++ API-referens
description: Lägger till de specificerade nätverksreferenserna i cachen.
type: docs
weight: 40
url: /sv/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) metod


Lägger till de specificerade nätverksreferenserna i cachen.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Resursens URI-prefix som referenserna är associerade med. |
| authenticationType | [String](../../../system/string/) | Autentiseringsschemat. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Referenserna att lägga till. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) metod


Lägger till de specificerade nätverksreferenserna i cachen.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```


### Argument

| Parameter | Type | Description |
| --- | --- | --- |
| host | [String](../../../system/string/) | Värdnamnet som referenserna är associerade med. |
| port | **int32_t** | Portnumret. |
| authenticationType | [String](../../../system/string/) | Autentiseringsschemat. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Referenserna att lägga till. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [NetworkCredential](../../networkcredential/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)