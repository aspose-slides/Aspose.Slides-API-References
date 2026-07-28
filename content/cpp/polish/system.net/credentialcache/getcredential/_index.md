---
title: GetCredential()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Zwraca poświadczenia dla określonego prefiksu URI i typu uwierzytelniania.
type: docs
weight: 66
url: /pl/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) metoda


Zwraca poświadczenia dla określonego prefiksu URI i typu uwierzytelniania.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Prefiks URI. |
| authenticationType | [String](../../../system/string/) | Typ uwierzytelniania. |

## CredentialCache::GetCredential(String, int32_t, String) metoda


Zwraca poświadczenia dla określonej nazwy hosta, portu i typu uwierzytelniania.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nazwa hosta, z którym powiązane są poświadczenia. |
| port | **int32_t** | Numer portu. |
| authenticationType | [String](../../../system/string/) | Typ uwierzytelniania. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [NetworkCredential](../../networkcredential/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [CredentialCache](../)
* Przestrzeń nazw [System::Net](../../)
* Biblioteka [Aspose.Slides](../../../)