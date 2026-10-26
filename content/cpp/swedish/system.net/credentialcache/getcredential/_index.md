---
title: GetCredential()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar autentiseringsuppgifter för det angivna URI-prefixet och autentiseringstypen.
type: docs
weight: 66
url: /sv/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) metod


Returnerar autentiseringsuppgifter för det angivna URI-prefixet och autentiseringstypen.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI-prefixet. |
| authenticationType | [String](../../../system/string/) | En autentiseringstyp. |

## CredentialCache::GetCredential(String, int32_t, String) metod


Returnerar autentiseringsuppgifter för det angivna värdnamnet, porten och autentiseringstypen.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| host | [String](../../../system/string/) | Värdnamnet som autentiseringsuppgifterna är associerade med. |
| port | **int32_t** | Portnumret. |
| authenticationType | [String](../../../system/string/) | Autentiseringstypen. |

## Se även

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [NetworkCredential](../../networkcredential/)
* Klass [Uri](../../../system/uri/)
* Klass [String](../../../system/string/)
* Klass [CredentialCache](../)
* Namnrymd [System::Net](../../)
* Bibliotek [Aspose.Slides](../../../)