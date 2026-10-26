---
title: GetCredential()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací pověření pro zadaný prefix URI a typ autentizace.
type: docs
weight: 66
url: /cs/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) metoda

Vrací pověření pro zadaný prefix URI a typ autentizace.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Prefix URI. |
| authenticationType | [String](../../../system/string/) | Typ autentizace. |

## CredentialCache::GetCredential(String, int32_t, String) metoda

Vrací pověření pro zadaný název hostitele, port a typ autentizace.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Název hostitele, ke kterému jsou pověření přiřazena. |
| port | **int32_t** | Číslo portu. |
| authenticationType | [String](../../../system/string/) | Typ autentizace. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [NetworkCredential](../../networkcredential/)
* Třída [Uri](../../../system/uri/)
* Třída [String](../../../system/string/)
* Třída [CredentialCache](../)
* Jmenný prostor [System::Net](../../)
* Knihovna [Aspose.Slides](../../../)