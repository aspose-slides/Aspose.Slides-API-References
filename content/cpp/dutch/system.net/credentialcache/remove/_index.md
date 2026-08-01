---
title: Remove()
second_title: Aspose.Slides voor C++ API-referentie
description: Verwijdert netwerkreferenties voor het opgegeven URI-prefix en authenticatietype.
type: docs
weight: 53
url: /nl/system.net/credentialcache/remove/
---
## CredentialCache::Remove(System::SharedPtr\<Uri\>, String) methode

Verwijdert netwerkreferenties voor het opgegeven URI-prefix en authenticatietype.

```cpp
void System::Net::CredentialCache::Remove(System::SharedPtr<Uri> uriPrefix, String authenticationType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Het URI-prefix. |
| authenticationType | [String](../../../system/string/) | Het authenticatietype. |

## CredentialCache::Remove(String, int32_t, String) methode

Verwijdert netwerkreferenties voor de opgegeven hostnaam, poort en authenticatietype.

```cpp
void System::Net::CredentialCache::Remove(String host, int32_t port, String authenticationType)
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | [String](../../../system/string/) | De hostnaam waaraan de referenties zijn gekoppeld. |
| port | **int32_t** | Het poortnummer. |
| authenticationType | [String](../../../system/string/) | Een authenticatietype. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Uri](../../../system/uri/)
* Class [String](../../../system/string/)
* Class [CredentialCache](../)
* Namespace [System::Net](../../)
* Library [Aspose.Slides](../../../)