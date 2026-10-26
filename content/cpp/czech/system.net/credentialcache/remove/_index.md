---
title: Remove()
second_title: Aspose.Slides pro C++ referenční API
description: Odstraňuje síťová pověření pro zadaný prefix URI a typ ověřování.
type: docs
weight: 53
url: /cs/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) metoda


Odstraňuje síťové pověření pro zadaný prefix URI a typ ověřování.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Prefix URI. |
| authenticationType | [String](../../../system/string/) | Typ ověřování. |

## CredentialCache::Remove(String, int32_t, String) metoda


Odstraňuje síťové pověření pro zadaný název hostitele, port a typ ověřování.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Název hostitele, ke kterému jsou pověření přiřazeny. |
| port | **int32_t** | Číslo portu. |
| authenticationType | [String](../../../system/string/) | Typ ověřování. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [CredentialCache](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)