---
title: Add()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt die angegebenen Netzwerk-Anmeldeinformationen dem Cache hinzu.
type: docs
weight: 40
url: /de/system.net/credentialcache/add/
---
## CredentialCache::Add(System::SharedPtr\<Uri\>, String, System::SharedPtr\<NetworkCredential\>) Methode

Fügt die angegebenen Netzwerk-Anmeldeinformationen dem Cache hinzu.

```cpp
void System::Net::CredentialCache::Add(System::SharedPtr<Uri> uriPrefix, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| uriPrefix | [System::SharedPtr](../../../system/sharedptr/)\<[Uri](../../../system/uri/)\> | Das URI-Präfix der Ressource, mit dem die Anmeldeinformationen verknüpft sind. |
| authenticationType | [String](../../../system/string/) | Das Authentifizierungsschema. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Die hinzuzufügenden Anmeldeinformationen. |

## CredentialCache::Add(String, int32_t, String, System::SharedPtr\<NetworkCredential\>) Methode

Fügt die angegebenen Netzwerk-Anmeldeinformationen dem Cache hinzu.

```cpp
void System::Net::CredentialCache::Add(String host, int32_t port, String authenticationType, System::SharedPtr<NetworkCredential> credential)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| host | [String](../../../system/string/) | Der Hostname, mit dem die Anmeldeinformationen verknüpft sind. |
| port | **int32_t** | Die Portnummer. |
| authenticationType | [String](../../../system/string/) | Das Authentifizierungsschema. |
| credential | [System::SharedPtr](../../../system/sharedptr/)\<[NetworkCredential](../../networkcredential/)\> | Die hinzuzufügenden Anmeldeinformationen. |

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Uri](../../../system/uri/)
* Klasse [String](../../../system/string/)
* Klasse [NetworkCredential](../../networkcredential/)
* Klasse [CredentialCache](../)
* Namensraum [System::Net](../../)
* Bibliothek [Aspose.Slides](../../../)