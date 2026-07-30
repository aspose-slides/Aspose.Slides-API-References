---
title: Add()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá zadané síťové přihlašovací údaje do mezipaměti.
type: docs
weight: 40
url: /cs/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) metoda

Přidá zadané síťové přihlašovací údaje do mezipaměti.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | URI předpona zdroje, ke které jsou přihlašovací údaje přiřazeny. |
| authenticationType | [String](../../../system/string/) | Schéma ověřování. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Přihlašovací údaje, které se přidají. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) metoda

Přidá zadané síťové přihlašovací údaje do mezipaměti.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Název hostitele, ke kterému jsou přihlašovací údaje přiřazeny. |
| port | **int32_t** | Číslo portu. |
| authenticationType | [String](../../../system/string/) | Schéma ověřování. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Přihlašovací údaje, které se přidají. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [Uri](../../../system/uri/)
* třída [String](../../../system/string/)
* třída [NetworkCredential](../../networkcredential/)
* třída [CredentialCache](../)
* jmenný prostor [System::Net](../../)
* Library [Aspose.Slides](../../../)