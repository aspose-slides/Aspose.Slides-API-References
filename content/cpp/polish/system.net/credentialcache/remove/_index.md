---
title: Remove()
second_title: Aspose.Slides dla C++ API Reference
description: Usuwa poświadczenia sieciowe dla określonego prefiksu URI i typu uwierzytelniania.
type: docs
weight: 53
url: /pl/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) metoda


Usuwa poświadczenia sieciowe dla określonego prefiksu URI i typu uwierzytelniania.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Prefiks URI. |
| authenticationType | [String](../../../system/string/) | Typ uwierzytelniania. |

## CredentialCache::Remove(String, int32_t, String) metoda


Usuwa poświadczenia sieciowe dla określonej nazwy hosta, portu i typu uwierzytelniania.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nazwa hosta, z którym powiązane są poświadczenia. |
| port | **int32_t** | Numer portu. |
| authenticationType | [String](../../../system/string/) | Typ uwierzytelniania. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [CredentialCache](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)