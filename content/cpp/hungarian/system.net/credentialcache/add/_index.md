---
title: Add()
second_title: Aspose.Slides C++ API referencia
description: Hozzáadja a megadott hálózati hitelesítő adatokat a gyorsítótárhoz.
type: docs
weight: 40
url: /hu/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) metódus

Hozzáadja a megadott hálózati hitelesítő adatokat a gyorsítótárhoz.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | A forrás URI előtagja, amelyhez a hitelesítő adatok tartoznak. |
| authenticationType | [String](../../../system/string/) | A hitelesítési séma. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | A hozzáadandó hitelesítő adatok. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) metódus

Hozzáadja a megadott hálózati hitelesítő adatokat a gyorsítótárhoz.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | [String](../../../system/string/) | A gazda neve, amelyhez a hitelesítő adatok tartoznak. |
| port | **int32_t** | A portszám. |
| authenticationType | [String](../../../system/string/) | A hitelesítési séma. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | A hozzáadandó hitelesítő adatok. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [NetworkCredential](../../networkcredential/)
* Osztály [CredentialCache](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)