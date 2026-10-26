---
title: GetCredential()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a megadott URI előtaghoz és hitelesítési típushoz tartozó hitelesítő adatokat.
type: docs
weight: 66
url: /hu/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) módszer

Visszaadja a megadott URI előtaghoz és hitelesítési típushoz tartozó hitelesítő adatokat.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az URI előtagja. |
| authenticationType | [String](../../../system/string/) | Egy hitelesítési típus. |

## CredentialCache::GetCredential(String, int32_t, String) módszer

Visszaadja a megadott host névhez, porthoz és hitelesítési típushoz tartozó hitelesítő adatokat.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | [String](../../../system/string/) | A host név, amelyhez a hitelesítő adatok kapcsolódnak. |
| port | **int32_t** | A port száma. |
| authenticationType | [String](../../../system/string/) | A hitelesítési típus. |

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [NetworkCredential](../../networkcredential/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [CredentialCache](../)
* Névterület [System::Net](../../)
* Library [Aspose.Slides](../../../)