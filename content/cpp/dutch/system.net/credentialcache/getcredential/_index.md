---
title: GetCredential()
second_title: Aspose.Slides voor C++ API-referentie
description: Retourneert referenties voor het opgegeven URI-voorvoegsel en authenticatietype.
type: docs
weight: 66
url: /nl/system.net/credentialcache/getcredential/
---
## CredentialCache::GetCredential(System::SharedPtr\<Uri\>, String) methode

Retourneert referenties voor het opgegeven URI-voorvoegsel en authenticatietype.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(System::SharedPtr<Uri> uriPrefix, String authenticationType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Het URI-voorvoegsel. |
| authenticationType | [String](../../../system/string/) | Een authenticatietype. |

## CredentialCache::GetCredential(String, int32_t, String) methode

Retourneert referenties voor de opgegeven hostnaam, poort en authenticatietype.

```cpp
System::SharedPtr<NetworkCredential> System::Net::CredentialCache::GetCredential(String host, int32_t port, String authenticationType) override
```

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| host | [String](../../../system/string/) | De hostnaam waaraan de referenties zijn gekoppeld. |
| port | **int32_t** | Het poortnummer. |
| authenticationType | [String](../../../system/string/) | Het authenticatietype. |

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [NetworkCredential](../../networkcredential/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [CredentialCache](../)
* Naamruimte [System::Net](../../)
* Bibliotheek [Aspose.Slides](../../../)