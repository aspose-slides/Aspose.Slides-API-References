---
title: Remove()
second_title: Aspose.Slides C++ API hivatkozás
description: Eltávolítja a hálózati hitelesítő adatokat a megadott URI előtaghoz és hitelesítési típushoz.
type: docs
weight: 53
url: /hu/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) metódus


Eltávolítja a hálózati hitelesítő adatokat a megadott URI előtaghoz és hitelesítési típushoz.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Az URI előtagja. |
| authenticationType | [String](../../../system/string/) | A hitelesítési típus. |

## CredentialCache::Remove(String, int32_t, String) metódus


Eltávolítja a hálózati hitelesítő adatokat a megadott gépnévhez, porthoz és hitelesítési típushoz.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| host | [String](../../../system/string/) | A gépnév, amelyhez a hitelesítő adatok tartoznak. |
| port | **int32_t** | A port száma. |
| authenticationType | [String](../../../system/string/) | Egy hitelesítési típus. |

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Uri](../../../system/uri/)
* Osztály [String](../../../system/string/)
* Osztály [CredentialCache](../)
* Névtér [System::Net](../../)
* Könyvtár [Aspose.Slides](../../../)