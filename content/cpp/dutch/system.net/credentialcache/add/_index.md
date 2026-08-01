---
title: Add()
second_title: Aspose.Slides voor C++ API-referentie
description: Voegt de opgegeven netwerkreferenties toe aan de cache.
type: docs
weight: 40
url: /nl/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) methode

Voegt de opgegeven netwerkreferenties toe aan de cache.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Het URI-voorvoegsel van de resource waarmee de referenties worden geassocieerd. |
| authenticationType | [String](../../../system/string/) | Het authenticatieschema. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | De toe te voegen referenties. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) methode

Voegt de opgegeven netwerkreferenties toe aan de cache.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | [String](../../../system/string/) | De hostnaam waarmee de referenties worden geassocieerd. |
| port | **int32_t** | Het poortnummer. |
| authenticationType | [String](../../../system/string/) | Het authenticatieschema. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | De toe te voegen referenties. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [NetworkCredential](../../networkcredential/)
* Klasse [CredentialCache](../)
* Namespace [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)