---
title: Add()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Dodaje określone poświadczenia sieciowe do pamięci podręcznej.
type: docs
weight: 40
url: /pl/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) metoda

Dodaje określone dane uwierzytelniające sieci do pamięci podręcznej.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Prefiks URI zasobu, z którym powiązane są poświadczenia. |
| authenticationType | [String](../../../system/string/) | Schemat uwierzytelniania. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Poświadczenia do dodania. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) metoda

Dodaje określone dane uwierzytelniające sieci do pamięci podręcznej.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| host | [String](../../../system/string/) | Nazwa hosta, z którym powiązane są poświadczenia. |
| port | **int32_t** | Numer portu. |
| authenticationType | [String](../../../system/string/) | Schemat uwierzytelniania. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Poświadczenia do dodania. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [Uri](../../../system/uri/)
* Klasa [String](../../../system/string/)
* Klasa [NetworkCredential](../../networkcredential/)
* Klasa [CredentialCache](../)
* Przestrzeń nazw [System::Net](../../)
* Library [Aspose.Slides](../../../)